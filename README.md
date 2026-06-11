# Delta Force Daily Codes Auto-Poster

自动每天9点(北京时间)将Delta Force游戏内的Daily Codes发布到Discord频道。

## 设置步骤

1. **创建GitHub仓库**
   - 登录GitHub，创建新仓库 `delta-force-codes`
   - 将此项目克隆到本地

2. **推送代码**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/delta-force-codes.git
   git push -u origin main
   ```

3. **启用Actions**
   - 进入仓库 → Actions → I understand my workflows, go ahead and enable them

4. **测试**
   - 进入 Actions → "Post Daily Codes to Discord" → Run workflow

## 自动运行时间
- 每天 UTC 1:00 (北京时间 9:00)

## 手动触发
- 进入 Actions → "Post Daily Codes to Discord" → "Run workflow"