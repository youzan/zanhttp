# ZanHttpDemo
zan php http server demo
# 如何使用
1. 安装swoole扩展，编译参数：
`--enable-async-mysql --enable-async-httpclient --enable-sockets --enable-async-redis`
（如有变动请参阅参数wiki: http://wiki.swoole.com/wiki/page/437.html）  
2. 安装composer
3. 在根目录下执行composer update
4. 配置php.ini
```ini
zan.RUN_MODE = test
zan.DEBUG = true
```
5. 启动http server
`php bin/httpd`
6. 访问`127.0.0.1:8030`




