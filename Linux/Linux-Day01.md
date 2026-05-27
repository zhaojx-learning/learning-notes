一、Linux 环境搭建
已完成
安装：
WSL2
Ubuntu 24.04 LTS
学习命令：
wsl --install
uname -a
二、Linux 基础命令
已掌握
pwd
ls
cd
mkdir
touch
作用：
| 命令    | 功能     |
| ----- | ------ |
| pwd   | 查看当前目录 |
| ls    | 查看文件   |
| cd    | 切换目录   |
| mkdir | 创建目录   |
| touch | 创建文件   |
三、Linux 文件操作
已掌握
cp
mv
rm
cat   猫
echo   回声
重点：
echo "Hello Linux" > hello.txtecho "Hello Linux" > hello.txt
理解：
输出重定向 >
Linux 空格敏感
文件复制/移动/删除
四、Linux 权限系统
已掌握
ls -l
chmod +x   chmod x
sudo
理解：
r = read   R =读
w = write
x = execute
以及：
root 用户
普通用户
sudo 权限提升
Linux 安全机制
五、vim 编辑器
已掌握
vim test.txt
学习：
| 操作   | 方法  |
| ---- | --- |
| 进入编辑 | i   |
| 退出编辑 | Esc |
| 保存退出 | :wq |
六、Linux 目录结构
/home   /家庭
/etc   /等
/var
/tmp
/usr
重点：
/var/log
作用：
存放系统日志
七、日志与文本处理
已掌握
grep
tail   尾巴
tail -f   尾巴- f
例如：
grep error app.log   Grep错误app.log
理解：
日志搜索
Linux 排错基础
错误信息分析
八、文件查找与系统监控
已掌握
find
ps aux
top   前
理解：
查找文件
查看 Linux 进程
CPU/内存监控
系统负载查看
九、nginx Web 服务部署
已完成
安装：
sudo apt install nginx -y
服务管理：
systemctl
学习：
start   开始
stop   停止
status   状态
enable   启用
成功：
✅ 启动 nginx
✅ 浏览器访问 localhost
✅ 修改 nginx 默认网页
十、Linux 网络基础
已理解
ip a   ip一
ping   平
curl   旋度
ss -tulpn
重点理解：
localhost   本地主机
对应：
127.0.0.1
即：
回环地址（自己访问自己）
理解：
IP   知识产权
端口
HTTP
80端口
服务监听
十一、SSH 远程连接
已完成
安装：
sudo apt install openssh-server -ySudo apt安装openssh-server -ysudo apt安装openssh-server -ySudo apt安装openssh-server -y
启动：
sudo systemctl start ssh   Sudo systemctl start SSHsudo systemctl start ssh sudo systemctl start sshsudo systemctl start ssh sudo systemctl start SSHsudo systemctl start ssh sudo systemctl start sshsudo systemctl start sshsudo systemctl start SSHsudo systemctl start sshsudo systemctl start SSHsudo systemctl start sshsudo systemctl start SSHsudo systemctl start sshsudo systemctl start SSHsudo systemctl start sshsudo systemctl start sshsudo systemctl start sshsudo systemctl start sshsudo systemctl start ssh
连接：
ssh zhao@localhost
理解：
SSH
22端口
known_hosts
SSH 指纹验证
Linux 远程管理


