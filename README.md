# spring cloud alibaba 服务搭建

### 1 选用组件

#### 1.1 注册与发现中心 nacos

**注：**spring boot、spring cloud  alibaba（spring cloud alibaba是基于spring cloud） 与nacos版本必须对应上。否则将会出现服务不能注册到nacos。

版本见：https://www.jianshu.com/p/12dbd51b2245

    不需要太多编码，首先要启动nacos的开源组件。
    其次在需要注册的服务中引入nacos的jar包引用，配置好nacos的地址后，在启动类上加入开启注册于发现的注解。启动服务即可将服务注册到注册中心。
    nacos支持集群部署。
    
    

#### 1.2 配置中心 nacos

### 2 服务介绍

#### 2.1 user-service用户服务





