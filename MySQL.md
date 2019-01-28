MySQL基础题：

1、什么是主键、外键

2、说一下数据库事务的特性

3、视图有什么用

4、drop,delete与truncate的区别

5、什么是索引，种类有哪些，索引方法有哪些

6、说一下你对改善SQL语句有的看法

7、select * from table1 where name=''zhangsan'' and tID > 10000和执行select * from table1 where tID > 10000 and name=''zhangsan''的速度是否一样

8、索引失效（全表扫描）的情况有哪些

9、简单说一下什么是聚集索引、非聚集索引

10、decimal(M,D)、float(M,D)、double(M,D)的区别是什么，说一下各自的使用场景

11、int(M)的M有什么用、float(M,D)的M和D呢、varchar(M)和char(M)的M又是干嘛的(字节数还是字符数)

12、varchar的最大长度是多少

13、一个字节等于多少bit，MySQL的int能存储的字节数是4，那么你怎么换算他的取值范围

14、Navicat给table建立索引的时候，索引类型有哪些，索引方法有哪些，各自的适用场景是什么
https://www.cnblogs.com/luyucheng/p/6289714.html

15、简述MySQL索引方法hash\btree两种的优缺点、适用场景
https://www.cnblogs.com/luyucheng/p/6289048.html
https://www.cnblogs.com/yuan-shuai/p/3225417.html

16、进行模糊查找的时候like '%abc%''\like 'abc%'会导致全表扫描吗

17、子查询跟join表哪个更快

18、简述MySQL的存储引擎MyISAM、InnoDB的各自的优缺点(至少5点)以及适用场景
http://www.cnblogs.com/luyucheng/p/6306512.html

19、简述行级锁、表级锁的各自的优缺点
http://www.cnblogs.com/luyucheng/p/6297752.html

20、InnoDB的行级锁定同样分为共享锁和排他锁两种类型，描述各自使用场景
http://www.cnblogs.com/luyucheng/p/6297752.html

21、MySQL的锁、事务、并发之间的关系是怎样的
https://www.cnblogs.com/chenqionghe/p/4845693.html

22、简述mysql主从复制原理以及作用

23、谈谈数据库优化的方式（建表、使用）

24、简述数据库三大范式

25、连表查询的种类

26、关于MySQL规范，你有什么建议（设计规范、设计原则）

27、innodb的事务与日志的实现方式（日志存放、如何通过日志实现事务）
https://www.cnblogs.com/panwenbin-logs/p/8366940.html

28、线上环境下MySQL数据库cpu飙升到500%的话该怎么处理
https://www.cnblogs.com/panwenbin-logs/p/8366940.html

29、备份计划，mysqldump以及xtranbackup的实现原理

30、你是如何监控你们的数据库的,你们的慢日志都是怎么查询的

31、表中有大字段X(例如：text类型)且字段X不会经常更新，以读为为主，请问您是选择拆成子表，还是继续放一起?写出您这样选择的理由

32、在当前的工作中，你碰到到的最大的 mysql db 问题以及如何解决的

33、请简洁地描述下 MySQL 中 InnoDB 支持的四种事务隔离级别名称，以及逐级之间的区别
https://www.cnblogs.com/panwenbin-logs/p/8366940.html

34、数据库事务的四个特性及含义

35、Mysql中什么时候会出现数据丢失、怎样预防数据丢失

36、简述Mysql集群 

37、有没接触过MySQL慢日志监控及报警