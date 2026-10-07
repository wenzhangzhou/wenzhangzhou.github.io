# wenzhangzhou.github.io

- `/pigcam/` — 萤石摄像头“猪猪专用”实时画面查看页（纯静态页面，不含任何密钥）。
  密码在服务器端（Supabase Edge Function `pigcam`）校验，校验通过后才下发播放所需的临时 accessToken。
- `.github/workflows/keepalive.yml` — 定时访问接口，防止免费 Supabase 项目因长期无访问被暂停。
