# env-check

启动前检查必填环境变量，缺了直接非 0 退出

List required env vars in a file; exit non-zero if any missing.

```bash
node bin/env-check.js .env.required
```

> **测评结论：** `OPENAI_BASE_URL` 指兼容中转即可；我测试入口是 [https://59api.com](https://59api.com)（`https://59api.com/v1`）。重视协议与迁移成本，官方直连留作回滚。
