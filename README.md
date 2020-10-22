README.md
练习参照
http://c.biancheng.net/view/5312.html
四-Spring Cloud开发环境
Spring Cloud开发环境的准备和Lombok安装步骤
1. JDK 1.8+
2. Maven 3.6+
3. Spring Tools 4 for Eclipse
4. Lombok 插件
五-Spring Boot简介
Spring Boot 开发的优点：
基于 Spring 开发 Web 应用更加容易。
采用基于注解方式的配置，避免了编写大量重复的 XML 配置。
可以轻松集成 Spring 家族的其他框架，比如 Spring JDBC、Spring Data 等。
嵌入式服务器，令开发和部署都变得非常方便。
六-搭建Spring Boot项目
1.pom.xml 中添加 Spring Boot 的依赖
pring-boot-starter-parent
spring-boot-starter-web
2.编写启动类
（亦可以新建springboot项目Spring Starter Project）
3.编写REST 接口
4.读取配置文件
1）Environment 
env.getProperty("server.port");
2）@Value("${server.port}")
3）自定义配置类
5.profiles 多环境配置
6.热部署
7.actuator 监控
自定义 actuator 端点[]统一异常处理[]异步执行[]随机端口[]
8.编译打包
