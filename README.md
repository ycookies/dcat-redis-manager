
<div align="center">
    <img src="https://jikeadmin.saishiyun.net/img/dcat-plus-logo.png" height="80"> 
</div>
<br>

<p align=""><code>Dcat-plus Admin</code>是一个基于<a href="https://www.laravel-admin.org/" target="_blank">laravel-admin</a>二次开发而成的后台系统构建工具，只需很少的代码即可快速构建出一个功能完善的高颜值后台系统。内置丰富的后台常用组件，开箱即用，让开发者告别冗杂的HTML代码，对后端开发者非常友好。</p>


- [官方网站](https://jikeadmin.saishiyun.net)
- [中文文档](https://jikeadmin.saishiyun.net/books/dcat-admin/#/)
- [github](https://github.com/ycookies/dcat-plus-admin)
- [Demo/在线演示](https://jikeadmin.saishiyun.net/admin)
- [示例源码](https://github.com/ycookies/dcatplus-demo)
- [技术社区](https://forum.saishiyun.net/t/dcat-admin)

### 作者
- Juenfy
- github:https://github.com/Juenfy/dcat-redis-manager

### <center>This is a redis manager for dcat-admin</center>

移植于laravel-admin扩展<a href="https://github.com/laravel-admin-extensions/redis-manager" target="_blank">redis-manager</a>

感谢作者开发的优秀扩展，侵权删！！！

### 环境要求
- redis
- dcat-plus/laravel-admin:*
- predis/predis:*

### 安装
```shell
composer require ycookies/dcat-redis-manager
```

把laravel默认的phpredis改成predis，.env配置添加
```env
REDIS_CLIENT=predis
```

关闭laravel默认的redis前缀，注释app\database.php
```shell
//            'prefix' => env('REDIS_PREFIX', Str::slug(env('APP_NAME', 'laravel'), '_').'_database_'),
```

### 截图
<img src="https://raw.githubusercontent.com/Juenfy/resources/refs/heads/master/1727601883198.jpg">

enjoy!!!
