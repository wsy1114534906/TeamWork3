# 项目团队

### CEO：裘王辉

- 负责项目全局监督
  - 仓库管理员权限
  - 关键里程碑规划与审批
  - Pull Request 最终审批人

### 产品部：张旭（CPO），赵宣皓，李哲

  - 负责产品文档：

    - `/docs/product_introduction`：产品概述、价值主张、核心功能等

    - `/docs/product_solution/`：对接技术部门，明确产品需要怎么更改

    - `/docs/user-guide/`：详细产品使用说明

    - `README.md`：项目概述、价值主张、核心功能

### 技术部：成涵吟（CTO），张倚中，严思雨，汪思远，刘子萌	

  - 负责代码开发，实现产品部门提出的要求：
    - `/src/`：源代码目录
    - `/config/`：配置文件
    - `/scripts/`：构建和部署脚本

### 知识部：雷智（CKO）

  - 知识管理与协作流程：
    - `/docs/meetings`：会议记录存档
    - `/docs/solutions/`：问题解决方案文档化
    - 管理 GitHub Issues：
      - 创建问题模板 (`.github/ISSUE_TEMPLATE/`)
      - 问题分类与标签管理
      - 定期整理和更新问题状态

# 项目仓库目录结构

```
project-repo/
├── .github/
│   ├── ISSUE_TEMPLATE/       # CKO: 问题模板
├── docs/
│   ├── Team/             # CKO: 会议记录
│   ├── Product/              # CPO: 产品规划
│   ├── Solutions/            # CKO: 解决方案文档
│   └── User-guide/           # CPO: 用户指南
├── src/                      # CTO: 源代码
├── config/                   # CTO: 配置文件
├── scripts/                  # CTO: 脚本文件
├── data/                     # 项目数据
├── CONTRIBUTING.md           # CTO: 贡献指南
└── README.md                 # CPO: 项目介绍
```

# 项目主计划

week-1团队分工与产品定义 (CEO,CPO团队）

Week-2 产品定义与产品方案 (CEO,CPO团队）

Week-3 产品方案与技术选型 (CEO,CTO团队）

Week-4 讨论与答疑 (CEO,CKO）

# 团队协同工作制度

1. **Issue 管理**
   - 新问题或任务先创建 Issue
   - CKO 负责对 Issue 进行分类、添加标签、分配负责人
   - 使用项目看板 (GitHub Projects) 跟踪任务状态
2. **代码与文档贡献**
   - 所有团队成员通过 Pull Request 提交更改
   - 分支命名规范：`feature/`, `bugfix/`, `docs/`, `config/` 等前缀
   - PR 模板中明确变更内容、关联的 Issue
3. **审核流程**
   - 代码由 CTO 及指定技术团队成员审核
   - 文档由 CPO 或 CKO 审核（根据文档类型）
   - CEO 对重大变更进行最终审批