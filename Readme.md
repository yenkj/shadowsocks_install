![Shadowsocks](https://github.com/teddysun/shadowsocks_install/raw/master/shadowsocks.png)
# Auto install Shadowsocks Server

shadowsocks.sh
===============
- Description: Auto Install Shadowsocks(Python) Server for CentOS/Debian/Ubuntu
- Intro: https://teddysun.com/342.html

shadowsocks-libev.sh
===============
- Description: Auto Install Shadowsocks(libev) Server for CentOS
- Intro: https://teddysun.com/357.html

shadowsocks-libev-debian.sh
===============
- Description: Auto Install Shadowsocks(libev) Server for Debian/Ubuntu
- Intro: https://teddysun.com/358.html

shadowsocks-go.sh
===============
- Description: Auto Install Shadowsocks(Go) Server for CentOS/Debian/Ubuntu
- Intro: https://teddysun.com/392.html

shadowsocks-crond.sh
===============
- Description: Check Shadowsocks(All version) Server is running or not, and start it if not running
- Intro: https://shadowsocks.be/6.html

shadowsocksR.sh
===============
- Description: Auto Install ShadowsocksR Server for CentOS/Debian/Ubuntu
- Intro: https://shadowsocks.be/9.html

shadowsocks-all.sh
==================
- Description: Auto Install Shadowsocks Server (all version) for CentOS/Debian/Ubuntu
- Intro: https://teddysun.com/486.html

haproxy.sh
===============
- Description: Auto Install haproxy for Shadowsocks Server
- Intro: https://shadowsocks.be/10.html

Copyright (C) 2014-2017 Teddysun

使用方法：
===============
- wget --no-check-certificate -O shadowsocks-libev.sh https://raw.githubusercontent.com/yenkj/shadowsocks_install/master/shadowsocks-libev.sh
- chmod +x shadowsocks-libev.sh
- ./shadowsocks-libev.sh 2>&1 | tee shadowsocks-libev.log

卸载方法：
===============
- ./shadowsocks-libev.sh uninstall
- 配置文件路径：/etc/shadowsocks.json

使用命令：
===============
- 启动：/etc/init.d/shadowsocks start
- 停止：/etc/init.d/shadowsocks stop
- 重启：/etc/init.d/shadowsocks restart
- 查看状态：/etc/init.d/shadowsocks status

使用
===============
1. 下载安装脚本
- wget https://raw.githubusercontent.com/yenkj/shadowsocks_install/master/shadowsocks.sh

2. 修改执行权限
- chmod 777 shadowsocks.sh

3.运行脚本及配置信息
- ./shadowsocks.sh
