# 8.30 周三
## 数据库的设计,个人信息页面的制作与修改
## 结果: 完成,没问题




# 8-31日 周四

## 任务:数据库管理和个人信息的验证

### 结果: 更新了数据库,遇到了数据库问题,注释有些人看不懂,所有更新了数据库还添加新功能,
### 新功能有:发布问题的标签,还有回答问题点赞,点赞有是否点赞,还有点赞的总数
### 个人信息显示已和数据库通讯,验证未完成.




# 9-1日 周五

## 任务:数据库管理还有左边的导航

### 结果:更新数据库,文档默认为空,遇到new Date的当前时间少于8小时,然后我去网上找了相关资料 得到两种解决方案,一种自己想的,一种网上查找   
### 解决方案:第一种{
** var ti = new Date().getFullYear()+"-"+(new Date().getMonth()+1)+"-"+new  Date().getDate()+ " "+(newDate().getHours()+8) +":"+new Date().getMinutes()+":"+new Date().getSeconds();  
var sj = new Date(ti); **    

注:将每个时间分别获取出来 然后将小时加八小时

** var time = new Date(Date.now() + (8 x 60 x 60 x 1000));  **  
注:这是加28800000毫秒也就是8个小时

### 个人信息的导航样式已经全部完成  有 个人信息,修改信息,钱包,我的问题,安全信息修改(修改密码,修改密保)
### }
