Java 基础

1、Object 对象的方法有哪些？分别有什么作用？该什么场景用？
2、Integer 的常量缓存池
3、Java 特性？什么是多态？举个例子
4、重载重写的区别？
5、画下 HashMap 的结构图？HashMap 、 HashTable 和 ConcurrentHashMap 的区别？使用场景分别是？
6、HashMap 中怎么解决冲突的？
7、ConcurrentHashMap 和 HashTable 中线程安全的区别？为啥建议用 ConcurrentHashMap ？能把 ConcurrentHashMap 里面的实现详细的讲下吗？
8、保证线程安全的还有其他的方式吗？
9、讲下 Synchronized？
10、讲下 RecentLock 可重入锁？ 什么是可重入锁？为什么要设计可重入锁？
11、Synchronized 和 RecentLock 有什么区别？这两个有没有深入了解源码？
12、讲下 Volatile 吧？他是怎样做到同步的？
13、Volatile 为什么不支持原子性？举个例子
14、Atomic 怎么设计的？有用过里面的类吗？
15、线程安全类和线程不安全的类，项目使用的时候你会怎么选择？怎么判断项目代码哪里会有线程不安全问题？
16、Map、List、Set 分别说下你了解到它们有的线程安全类和线程不安全的类？
17、TreeSet 清楚吗？能详细说下吗？
18、ThreadLocal 了解吗？项目有用过吗？可以说说
19、JUC 里面你还知道什么其他的类吗？比如 CountDownLatch、Condition
20、从源码详细说下 Java 里面的线程池吧，使用线程池有什么要注意的地方？你们公司有规范吗？

JVM

1、JAVA 类加载器
2、Java 内存结构（注：不是 Java 内存模型，别搞混）
3、怎么判断对象是否可 GC？Java 对象有哪些引用类型？有什么区别？
4、OOM 出现的有哪些场景？为什么会发生？
5、Minor GC 和 Full GC 有什么区别？分析过 GC 日志吗？
6、说下你知道的垃圾回收算法
7、说下你知道的垃圾收集器
8、CMS 和 G1 的区别知道吗？使用场景分别是？你项目中用的是哪个？
9、你还知道哪些 JVM 调优参数？
10、假如线上服务发生 OOM，有哪些措施可以找到问题？
11、假如线上服务 CPU 很高该怎么做？有哪些措施可以找到问题？
12、假如线上应用频繁发生 Full GC，有哪些措施可以找到问题？
13、一般线上环境遇到 JVM 问题，你会使用哪些工具来分析？找到问题后又该如何去解决呢？

Spring

1、说下你对 Spring 生态的了解？
2、说下你对 Spring AOP 和 IOC 的理解？看过实现原理吗？
3、说下 Bean 在 Spring 中的生命周期？
4、讲下你知道的 Spring 注解有哪些？该什么场景使用？
5、Spring 事务知道吗？有了解过吗？
6、说下你刚才说的 SpringBoot 吧，你觉得 SpringBoot 有什么优点？
7、SpringBoot 自动化配置是怎么做的？有看过实现源码吗？
8、Spring Boot 中最核心的注解 SpringBootApplication 有看过源码分析过吗？
9、你的项目中 SpringBoot 用到了哪些和其他技术栈整合的？
10、使用 Spring 或者 SpringBoot 有遇到过什么印象深刻的问题吗？当时是怎么解决的？

数据库

1、你的项目使用的是什么数据库？
2、你对数据库了解多少？说下数据库的索引实现和非主键的二级索引
3、说下 MySQL 的索引原理
4、讲下 InnoDB 和 MyISAM 的区别？使用场景是？
5、有和 ElasticSearch 的索引原理对比过吗？
6、如何判断一个查询 sql 语句是否使用了索引？
7、数据库事务特性和隔离级别
8、项目数据库表是你设计的吗？一般要注意什么？如何考虑扩展性？
9、项目 MySQL 的数据量和并发量有多大？量大后的影响有哪些，有考虑吗？SQL 调优有哪些技巧？
10、说下你项目里面关于数据库印象最深的一个问题？当时是怎么解决的

其他

1、描述下网页一个 Http 请求到后端的整个请求过程
2、有比较过 Http 和 RPC 吗？如果叫你设计一个高性能的 Http 或者 RPC，你会从哪些方面考虑？
3、项目中我看使用了 xxx （ElasticSearch、Hbase、Redis、Flink 等），有深入了解它们的原理和懂点调优技巧吗？
4、项目中我看使用了 xxx （ElasticSearch、Hbase、Redis、Mysql 等），有深入了解它们数据同步是怎么做吗？
5、项目中我看使用了 xxx （ElasticSearch、Hbase、Redis、Mysql 等），有深入了解它们常见的监控指标吗？
6、如果叫你设计一个秒杀系统，你会从哪些方面考虑？
7、如果叫你设计一个电商系统，你会从哪些方面考虑？
8、如果叫你设计一个监控告警系统，你会从哪些方面考虑？
