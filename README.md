flowchart LR
    A[📨 消息来源<br>Webhook/API] --> B[🔧 预处理]
    B --> C[⚡ Apprise中间件]
    C --> D[💬 微信]
    C --> E[📢 钉钉]
    C --> F[📧 邮件]
    C --> G[🔄 其他]
