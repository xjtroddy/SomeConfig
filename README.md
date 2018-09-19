# iterm2 配置

## itermConfig
iterm2+oh-my-zsh+agnoster

### 下载 iterm2
brew cask install iterm2

### 安装 oh-my-zsh
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

官网：https://ohmyz.sh/

### 安装agnoster主题
编辑~/.zshrc修改主题为：agnoster

### 下载powerline字体
https://github.com/powerline/fonts
运行 ./install
更改iterm2的字体为Meslo powerline

### 进一步优化
精简 user@hostname：添加export DEFAULT_USER="username"到~/.zshrc中
