# 实体：FU 技能系统

## 已安装技能 (12)
1. agent-autonomy-kit - 主动任务队列
2. elite-longterm-memory - 分层记忆
3. find-skills - 技能发现
4. gateway-watchdog - 自我修复
5. github - GitHub 集成
6. gog - Google Workspace
7. proactive-agent - 自动经验捕获
8. skill-vetter - 安全检查
9. summarize - 内容总结
10. tavily-search - 联网搜索
11. weather - 天气查询

## 核心依赖
- tavily-search → TAVILY_API_KEY
- github → gh CLI
- gog → gog CLI

## 安全等级
- 🟢 低：weather, find-skills
- 🟡 中：tavily-search, gateway-watchdog
- 🔴 高：github, gog（需凭证）
