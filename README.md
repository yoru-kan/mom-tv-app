# 老妈专用TV 自动更新

电视上的 APP 每天检查一次 `mom/update.json`，有新版本就从 jsDelivr 分段下载 APK（每段 < 20 MB），校验 SHA256 后提示安装。

由 `tools\\publish_app.py` 发布，不要手动改。
