# Prompt themes

A unified collection of custom themes for Starship and Oh My Posh.  
This repository centralizes configuration, shared assets, and utilities for maintaining consistent terminal prompts
across shells and operating systems.

## Usage for Starship

```shell
# On Linux or macOS
export STARSHIP_CONFIG=~/example/non/default/path/starship.toml
eval "$(starship init zsh)"

# On Windows PowerShell
$ENV:STARSHIP_CONFIG = "$HOME\example\non\default\path\starship.toml"
Invoke-Expression (&starship init powershell)
```

## Usage for Oh My Posh

```shell
# On Linux or macOS
export POSH_THEME=~/example/non/default/path/oh-my-posh.yaml
eval "$(oh-my-posh init zsh --config $POSH_THEME)"

# On Windows PowerShell
$ENV:POSH_THEME  = "$HOME\example\non\default\path\oh-my-posh.yaml"
oh-my-posh init pwsh --config $ENV:POSH_THEME | Invoke-Expression
```
