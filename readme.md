# 葉子羽
## 智慧商務系
### 大學生

```python=
print("hello")
```
**從未追蹤到交到 Git 儲存庫中**
git status 查看狀態
![image](https://hackmd.io/_uploads/SyyezylC0.png)
untracked未追蹤
![image](https://hackmd.io/_uploads/rJlvp1gAR.png)

1. ```git add README.md```將 ==[README.md 檔案添加到 Git 的暫存]== ，準備提交。
2. ```git commit -m "first commit"```將 ==[暫存區放到本地端]== ，並為這次提交加上訊息 first commit : 標註，表示這是第x次提交。
3. ```git push -u origin main``` ==[將本地的 main 分支推送到遠端儲存庫 origin]== 。-u 選項會將本地分支和遠端分支進行關聯（upstream），以後執行 git push 時不需要再指定遠端和分支名稱。