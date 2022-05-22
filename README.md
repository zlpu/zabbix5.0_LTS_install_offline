## 使用方法：


### 适用环境：Centos7上离线安装ZABBIX5.0LTS，覆盖安装Mysql、nginx、zabbix，如有必要请先做数据备份或者不要执行这个脚本。


#### 脚本中已经定义mysql的root密码为passwd123,zabbix用户的密码需要自己输入


#### nginx端口使用了80端口

1.将zabbix5.0_LTS-os7-rpm.tar.gz压缩包上传到服务器的/root目录下


2.运行脚本前系统中不能有/zabbix这个目录


3.运行脚本


sh zabbix5_centos7_offline_install

![image](https://user-images.githubusercontent.com/46338963/169682360-a77b0c41-078a-4c84-9394-b068d463991d.png)
![image](https://user-images.githubusercontent.com/46338963/169682363-7b455e7a-c96c-4ddb-a99d-a034ad4258c9.png)
![image](https://user-images.githubusercontent.com/46338963/169682372-1e247b9f-9708-47d4-a326-60ebcafdba5a.png)
