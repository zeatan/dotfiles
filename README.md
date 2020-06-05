# dotfiles

## Requirements

- Zsh installed   
- Zplug installed and path setting
- coreutils installed

## Steps

1. Clone repository on home  
   ```bash
   cd $HOME
   git clone https://github.com/zeatan/dotfiles
   ```
2. Symlink dot files to $HOME
   ```bash
   ln -snfv dotfiles/git/.gitconfig .gitconfig
   ln -snfv dotfiles/zsh/.zshrc .zshrc
   ```
3. Load zshrc
   ```bash
   source .zshrc
   ```
