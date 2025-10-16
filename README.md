# 🎯 协会会员管理系统

> **一个基于 Vue 3 与 Spring Boot 的全栈练习项目**

[![Vue](https://img.shields.io/badge/Vue-3.3-4fc08d?logo=vuedotjs)](https://vuejs.org/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7-6db33f?logo=springboot)](https://spring.io/projects/spring-boot)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479a1?logo=mysql)](https://www.mysql.com/)

## 📖 项目简介

这是一个为协会组织开发的**全栈会员管理系统**，主要用于团队成员学习和实践现代Web开发技术。

- **前端**：会员可查看个人信息、缴纳会费、报名活动
- **后台**：管理员可管理会员信息、处理会费、发布活动
- **目标**：通过完整项目流程，掌握前后端分离开发的核心技能

## 🚀 功能特性

| 模块 | 功能点 |
| :--- | :--- |
| **会员管理** | 会员注册/登录、信息维护、状态管理 |
| **会费管理** | 会费标准设置、缴费记录查询、状态跟踪 |
| **活动管理** | 活动创建发布、在线报名、名单管理 |
| **系统管理** | 权限控制、数据统计、操作日志 |

## 🛠️ 技术栈

### 前端技术
- **框架**: Vue 3 + TypeScript + Vite
- **状态管理**: Pinia
- **UI组件**: Element Plus
- **路由**: Vue Router
- **HTTP客户端**: Axios

### 后端技术
- **框架**: Spring Boot 2.7.x
- **安全框架**: Spring Security + JWT
- **数据访问**: MyBatis-Plus
- **数据库**: MySQL 8.0
- **API文档**: Knife4j

## 📁 项目结构

```

association-management/
├──frontend/                 # Vue前端项目
│├── src/
││   ├── views/           # 页面组件
││   ├── components/      # 通用组件
││   ├── stores/          # 状态管理
││   └── utils/           # 工具函数
├──backend/                 # Spring Boot后端项目
│├── src/main/java/
││   ├── controller/      # 控制层
││   ├── service/         # 业务层
││   ├── mapper/          # 数据层
││   └── entity/          # 实体类
│└── src/main/resources/
│└── application.yml  # 配置文件
└──README.md               # 项目说明

```

## ⚡ 快速开始

### 环境要求
- Node.js 16+
- JDK 8+
- MySQL 8.0

### 前端运行
```bash
cd frontend
npm install          # 安装依赖
npm run dev          # 启动开发服务器
```

访问: http://localhost:5173

### 后端运行

1. 在MySQL中创建数据库 association_db
2. 修改 application.yml 中的数据库配置
3. 运行主程序:

```bash
cd backend
mvn spring-boot:run
```

访问: http://localhost:8080
API文档:http://localhost:8080/doc.html

数据库初始化

SQL脚本位置: backend/sql/init.sql

## 👥 团队成员与分工

| 成员 | 角色 | 主要职责 |
| :--- | :--- | :--- |
| 同学A | 前端工程师 | 会员端页面开发、全局状态管理 |
| 同学B | 前端工程师 | 管理后台开发、UI组件库搭建 |
| 同学C | 后端工程师 | 会员/活动模块API、业务逻辑 |
| 同学D | 后端工程师 | 认证授权、会费模块API、系统安全 |
| 同学E | 项目经理 | 进度协调、部署运维、文档编写 |

## 🔧 开发规范

### Git分支管理
- `main` - 主分支，保持稳定
- `develop` - 开发分支  
- `feature/xxx` - 功能分支
- `hotfix/xxx` - 紧急修复分支

### 代码提交
使用约定式提交：
- `feat:` 新功能
- `fix:` 修复bug
- `docs:` 文档更新
- `style:` 代码格式调整

## 📝 学习目标

通过本项目，团队成员将掌握：
- ✅ Vue 3组合式API和TypeScript
- ✅ Spring Boot后端RESTful API开发
- ✅ JWT身份认证与权限控制
- ✅ 前后端分离架构与联调
- ✅ Git团队协作开发流程
- ✅ 项目部署与运维基础

## 📄 相关文档

- [API接口文档](http://localhost:8080/doc.html) (运行后端后访问)
- [数据库设计文档](./docs/database.md)
- [部署说明](./docs/deployment.md)

## 📞 联系我们

如有问题，请在项目Issues中提出或联系团队成员。

---

**祝您编码愉快！** 🎉

