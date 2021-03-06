## 第一部分

### Linux shell程序设计
- 编写一个实用于CentOS的开机系统优化的shell程序，该shell程序至少需要具备如下功能中的10个功能：
  - 1)	先对系统进行判断，如果是Cent OS 64位，就继续运行。
  - 2)	先将系统的安装源设置为网易的（网易的安装源算是国内比较稳定的）
  - 3)	安装EPEL的源和RPMforge的源，以利用第三方的源来让yum安装起来更方便
  - 4)	更新软件
  - 5)	设置为每天上午十点进行时间同步（跟国家授时中心的服务器进行时间同步）
  - 6)	将系统同时打开的文件个数增大
  - 7)	将ctrl ALT delete键进行屏蔽，防止误操作的时候服务器重启
  - 8)	关闭 SELinux 
  - 9)	禁用GSSAPI来认证
  - 10)	也禁用 DNS 反向解析
  - 11)	加快SSH 登陆速度
  - 12)	优化一些内核参数
  - 13)	调整删除字符的按键为backspace（某些系统默认是delete）
  - 14)	打开vim的语法高亮
  - 15)	取消生成whatis 数据库和locate数据库
  - 16)	关闭没用的服务
  - 17)	关闭 IPv6 

- 2.有10台被监控主机，一台监控机，在监控机上编写脚本，一旦某台监控机器/分区使用率大于80%，就发出报警，放到crontab里面，每10分钟检查一次。

- 3．设计一个shell程序，在每月第一天备份并压缩/etc目录的所有内容，存放在/root/bak目录里，且文件名为如下形式yymmdd_etc，yy为年，mm为月，dd为日。Shell程序fileback存放在/usr/bin目录下。

- 4. 用Shell编程，判断一文件是不是块或字符设备文件，如果是将其拷贝到/dev目录下。

- 5. 设计一个shell程序，添加一个新组为class1，然后添加属于这个组的30个用户，用户名的形式为stdxx，其中xx从01到30。

## 第二部分

### linux设备驱动程序设计
  - 1. 编写一个linux的设备驱动程序（为简单起见，建议编写一个字符设备驱动程序），必须满足如下要求：
      - 1)	需要有一个设备驱动程序
      - 2)	需要有一个测试程序，以验证设备驱动程序的功能。

- [参考文档](https://www.cnblogs.com/chen-farsight/p/6155518.html#unit3.1.5)
- [参考文档（首选）](http://blog.csdn.net/creazyapple/article/details/7290680)

## XAMPP
- [xampp](https://www.apachefriends.org/faq_linux.html)
- Path
  > XAMPP will be installed to /opt/lampp
- Start xampp
  > sudo /opt/lampp/lampp start
- Stop xampp
  > sudo /opt/lampp/lampp stop
