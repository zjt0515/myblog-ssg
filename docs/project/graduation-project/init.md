---
sidebar_position: 2
---
# Init

基于 Web 的在线评测系统，支持多语言代码提交、自动编译与运行、结果判定及排行榜展示。系统采用前后端分离架构，引入任务队列与沙箱化执行环境，以提升系统的安全性与可扩展性。

## My Ideas

1. 前端 React 
   1. 熟悉Vue, 想学习React
2. 后端 NestJS/SpringBoot
3. 数据库 Mysql


### Core Algorithm/Problems

1. 代码沙箱：安全隔离的环境 -> 防止用户代码越界访问
2. 判题规则算法：验证用户代码结果
3. 任务调度算法：用户量 > 服务器资源的情况下，对用户依次排队

## References
documents

1. Building a Leetcode clone backend
2. https://arxiv.org/pdf/1710.05913
3. https://www.domjudge.org/docs/amrita-domjudge.pdf?utm_source=chatgpt.com

code (open-source oj)

1. [hustoj](https://github.com/zhblue/hustoj)
   1. php
2. [qdu-oj](https://github.com/QingdaoU)
   1. python, django + vue
3. [sdu-oj](/)
   1. java, springboot + vue
4. [judge0](https://github.com/judge0/judge0)
