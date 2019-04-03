# 错误显示
>[Running] cmd /c "d:\pleiades\workspace\KQ-html\WebContent\arcgis\backup.bat"
>
>d:\pleiades\workspace\KQ-html\WebContent\arcgis>xcopy /Y /E /D "\\172.29.60.1\download\F13074\Downloads\arcgis" "D:\pleiades\workspace\KQ-html\WebContent\arcgis" 
>0 �̃t�@�C�����R�s�[���܂���

>
>[Done] exited with code=0 in 0.365 seconds

# 改为终端显示
按下`F1`，打开命令行 → 输入`setting.json`，打开文件 ⇒ 加入下列字符:
>{
>
>   "code-runner.runInTerminal": true //输出 改为 终端
>
>}

