Git & Redis:

1. git 提交到暂存区和仓库区的命令分别是什么?

     git add .   git commit -m 备注信息

     

2. git 在本地电脑中分为几部分? 

     三个部分  工作区  暂存区  仓库区

     

3. git 撤销工作区与暂存区的命令是什么?

   撤销工作区：git checkout 文件名

   撤销暂存区到工作区: git reset HEAD 文件名

   

4. redis服务端有几种数据结构, 分别是什么?

     redis 中的五种数据类型，string, list, set, zset, hash

    

5. redis默认有几个数据库?

     默认有16个数据库

    

6. 进入redis服务端的命令是什么? 进入客户端呢?

     redis-server

       redis-cli

代码题: 

在github中创建一个名为 hello_world 的仓库, 把该仓库clone到本地, 在本地的hello_world中创建一个名为 login.py 的文件, 内部分别定义三个变量, 每次定义一个变量就需要提交到远端仓库一次. 一共提交三次, 每次的注释必须写清楚: 第一次变量提交, 第二次....

检查时会查看远端仓库提交记录.

