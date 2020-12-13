# OhGodMusicBot
A v10 Discord.JS music bot in 100 lines or less

## Installation (Windows)

This section is for running the bot locally on Windows. If you're on Mac it should be similar. I'll assume Linux users can figure it out.

### Download Node.js

Node.js is what will be used to run the bot.
Download [Node.js 6.X from the website](https://nodejs.org/en/).

### Install Node.js

Open the Node.js Setup.
In the options, make sure `Node.js runtime` `npm package manager` and `Add to PATH` are enabled. After that install Node.js.

### Install Windows-Build-Tools

Open up a windows powershell and run `npm i -g windows-build-tools`. This will take a while as it will download and install both python 2.7 and c++ build tools, so you can run node-gyp builds.

### Download Git

And install it. The website is http://git-scm.com and make sure you choose "for command prompt".

---

### FFMPEG をダウンロード

(64-bit) [ここをクリック](https://www.gyan.dev/ffmpeg/builds/ffmpeg-release-full.7z)して FFMPEG をダウンロードしましょう。</br>
(32-bit) 少々古いですが、問題ありません。[ここをクリック](https://drive.google.com/uc?export=download&id=0B91Dn6OTKxuFU1hNc2hPWmZVVG8)して FFMPEG をダウンロードしましょう。

### FFMPEG をインストール/設定

ドライブの直下(c:\\)にファイルを解凍し、`ffmpeg` にリネームします。

**それができたら、FFMPEG を環境変数に追加しましょう**

1. コマンドプロンプトを管理者で開きます。
2. `setx Path "%path%;c:\ffmpeg\bin" /M` と打ち込みます。(手動ではなくこれをコピーすることをおすすめします)

---

### Download and Install OhGodMusicBot

Next you'll need to download the bot and configure it.
Download the master branch and put the unzipped files in a new folder on your computer.
Next rename .json.example to .json and enter the correct information. *Note: You will have to remove any and all comments from the .json.example file, as they are not supported in json. They are there to guide you as you decide how you want to configure your bot*

For obtaining a Discord Bot token, please see [this page.](https://discordapp.com/developers/docs/intro)

Before running the bot you need to install the dependencies.
In the folder you put the files in, Shift+Right click and select open command window here.
In the command prompt type `npm install`.

The bot should now be ready!
Open a command prompt like above and type `npm start` to start the bot and see if it works.

### Install dependencies

**Windows**

Shift-RightClick in the folder that you downloaded and select Open command window here. Then type `npm install` and hit Enter.

**Linux**

cd to where you cloned the GitHub repo and type `npm install`. This will take a while.
