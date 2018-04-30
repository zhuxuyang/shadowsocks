Removed according to regulations.
配置说明:
server: 服务器公网IP;
local_address: 本地代理地址;
local_port: 本地代理端口;
port_password: 自己设定的服务器端口和密码;
timeout: 超时断开, 以秒为单位;
method: 加密方式;
fast_open: 是否使用TCP;
workers: workers是进程数,默认为1. 只在Unix和Linux下有用.这里没有指定.

作者：suanite
链接：https://www.jianshu.com/p/8151bfd9a760
來源：简书
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。


{
     "server": "a.b.c.d",  
     "local_address": "127.0.0.1",
     "local_port": "1080",
     "port_password": {
       "9876": "xx",
       "9875": "xx"
     },
   "timeout": 300,
   "method": "rc4-md5",
   "fast_open": true
   }
