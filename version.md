# 添加修改的文件
git add manifest.json package.json

# 提交更改
git commit -m "release: v1.0.1"

# 创建新标签
git tag -a 1.0.1 -m "version 1.0.1"

# 推送代码和标签
git push origin main --tags