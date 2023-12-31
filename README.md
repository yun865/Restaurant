项目简介：
本项目是专门为校园食堂餐饮企业定制的一款软件产品，包括系统管理后台和小程序端应用两部分。其中系统管理后台主要提供给餐饮企业内部员工使用，可以对餐厅的分类、菜品、套餐、订单、员工等进行管理维护，对餐厅的各类数据进行统计并且生成实时的订单数据统计效果图，同时也可进行来单语音播报功能。小程序端主要面向给学生，教师等校内人员使用，可以在线浏览菜品、添加购物车、下单、支付、催单等。

项目内容：
使用Spring，SpringMVC、Mybatis框架，实现对员工、菜品、订单购物车的增删改查操作。
使用Nginxt作为Http服务器，部署静态资源实现反向代理和Tomcat的负载均衡。
使用Redis实现缓存功能，整合Spring Cache框架将减少方法的执行次数，提高应用程序的性能和响应速度，减轻数据库等后端资源的压力。
使用WebSocket协议和Apache ECharts数据可视化图表库实现营业额统计、用户统计、订单统计 、销量排名。
使用Apache POI实现数据读写Excel文件中的数据

个人职责：
在项目中承担员工，菜品的分页查询，使用MyBatis的插件PageHelper，解决分页查询功能
在项目中承担后端访问Redis服务的任务，配置Redis数据源，使用Spring Data Redis中的RedisTemplate类来简化 Redis 操作，数据缓存在Redis中，缓解MySQL高频访问。
使用SpringSecurity、JWT认证，完成用户认证授权开发

小程序：
（1）订单首页

![（1）订单首页](https://github.com/HelloWorld-Me-You/CampusSmartRestaurant/blob/master/订单首页.png)


（2）提交订单

![提交订单](https://github.com/HelloWorld-Me-You/CampusSmartRestaurant/blob/master/提交订单.png)

（2）支付页面

![成功支付](https://github.com/HelloWorld-Me-You/CampusSmartRestaurant/blob/master/成功支付.png)


（3）订单详情

![订单详情](https://github.com/HelloWorld-Me-You/CampusSmartRestaurant/blob/master/订单详情.png)

（4）催单

![催单](https://github.com/HelloWorld-Me-You/CampusSmartRestaurant/blob/master/催单.png)

管理端
登录：

![管理端登录界面](https://github.com/HelloWorld-Me-You/CampusSmartRestaurant/blob/master/管理端登录界面.png)

首页：

![工作台](https://github.com/HelloWorld-Me-You/CampusSmartRestaurant/blob/master/工作台.png)


数据统计

![数据统计](https://github.com/HelloWorld-Me-You/CampusSmartRestaurant/blob/master/数据统计.png)


订单管理：

![订单管理](https://github.com/HelloWorld-Me-You/CampusSmartRestaurant/blob/master/订单管理.png)


菜品管理：

![菜品管理](https://github.com/HelloWorld-Me-You/CampusSmartRestaurant/blob/master/菜品管理.png)


分类管理：

![分类管理](https://github.com/HelloWorld-Me-You/CampusSmartRestaurant/blob/master/分类管理.png)

员工管理：

![员工管理](https://github.com/HelloWorld-Me-You/CampusSmartRestaurant/blob/master/员工管理.png)


