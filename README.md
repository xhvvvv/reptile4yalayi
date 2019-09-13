# Reptile4Yalayi
雅拉伊网站爬虫，嘿嘿嘿，你懂的

## 开始出发！

> 网站入口：https://www.yalayi.com/

![](readme/yalayi.png)

### spring boot 配置文件参考：

```yml
server.port=8088

spring.datasource.url=jdbc:mysql://localhost:3306/dev?useUnicode=true&characterEncoding=UTF-8
spring.datasource.username=root
spring.datasource.password=Mysql@2019
spring.datasource.driverClassName=com.mysql.cj.jdbc.Driver
```
## 成果展示
![](readme/demo.png)

![](readme/total.png)

## 注意事项
![](readme/todo.png)

- 如果没有会员的话，这种方式能爬到的图并不多，截止 2019-09-13，本人能统计到雅拉伊网站图片总数有 16313 张（366 个相册），以免费用户只能爬到 1708 张，充值 30 元的情况下能爬到 10314 多张。
- 如果各位大神有能爬到付费资源的方法，欢迎交流。
