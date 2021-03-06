## Settings

- Automatically save settings after a certain time
  - Configuration → Startup & Exit → Autosave
- Select items by clicking on the [line number](https://www.xyplorer.com/release_12.70.php#LNS)
  - General → Menus, Mouse, Safety → Mouse → Line number selection
- Rename by [Up and Down keys](https://www.xyplorer.com/release_9.80.php#SerialRenameUpDown)
  - General → Sort and Rename → Rename → Serial rename by Up and Down keys
- Enable background processing for all file operations
  - File Operations → File Operations → ☑ Enable background processing (☑ Apply to...)
- Use the [Live Filter Box](https://www.xyplorer.com/release_17.00.php#LFB) as default typeahead search:
  - Filters & Type Ahead Find → Type Ahead Find → Enable type ahead find
  - Configuration → Filters & Type Ahead Find → Type Ahead Find → Redirect typing to Live Filter Box

## Features

- [Action Log](https://www.xyplorer.com/release_8.60.php#actionlog)
  - Edit → Action Log ...
- [Custom File Icons](https://www.xyplorer.com/release_12.40.php#CFI)
  - Tools → Customize File Icons... (`Ctrl + I`)
- [Live Filter Box](https://www.xyplorer.com/release_17.00.php#LFB)
- [Mouse Down Blow Up](https://www.xyplorer.com/highlights.php#mdbu)
- [Paper folders](https://www.xyplorer.com/release_14.30.php#PF)
- [Quick select](https://www.xyplorer.com/release_15.00.php#QuickSelect)
- [Sync Folderrs](https://www.xyplorer.com/release_18.40.php#Sync)
- [Tabsets](https://www.xyplorer.com/release_10.70.php#tabsets)

## Scripts

- Flatten folder: `flattenfolder();`

## Apps

- Avidemux: `run """avidemux.exe"" ""<curitem>"" --output-format MP4v2";`
- ConEmu: ` run """ConEmu.exe"" -Dir <curpath> -run {Bash::Git bash} -new_console"`

## Load script file

```
::load "script-file"
```

## User Defined Buttons

- Notepad++
  - Command: `run "C:\Program Files (x86)\Notepad++\notepad++.exe" <selitems>`
  - Icon: C:\Program Files (x86)\Notepad++\notepad++.exe

## List management

### Find Files → Excluded Files

```
*.git*
*node_modules*
```
