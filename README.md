# spring-mybatis-test
mybatis for adu.
MyBatis查询两个字段，返回Map，一个字段作为key，一个字段作为value的实现

https://www.cnblogs.com/waterystone/p/6214322.html?utm_source=itdadao&utm_medium=referral

1. 问题描述
　　在使用MyBatis，我们经常会遇到这种情况：SELECT两个字段，需要返回一个Map，其中第一个字段作为key，第二个字段作为value。MyBatis的MapKey虽然很实用，但并不能解决这种场景。这里，就介绍一种使用拦截器来解决这个问题的方案。

2. 解决方案
源码详见：spring-mybatis-test
