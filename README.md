# 内网穿透

[Frp](https://github.com/fatedier/frp)


## 服务端配置

1. 在 `~/.config/systemd/user` 目录下创建 `frps.service`，复制当前文件内容；
2. 启动：`systemctl --user enable frps.service`
3. 启动：`systemctl --user start frps`

## 本地使用
