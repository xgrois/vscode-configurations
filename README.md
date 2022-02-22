# VS Code Extensions
## _Generic_

| Extension | Author | Marketplace | For | Comments | MyStars |
| ------ | ------ | ------ | ------ | ------ | ------ |
| Glasslt-VSC | hikarin522 | [link](https://marketplace.visualstudio.com/items?itemName=s-nlf-fh.glassit) | Add transparency to the IDE | Love it | 10/10 |
| Prettier | Prettier | [link](https://marketplace.visualstudio.com/items?itemName=s-nlf-fh.glassit) | Enforces a consistent style | Only for frontend dev (HTML, CSS, JS, TS, Angular, YAML, JSON). Don't like it supress line spaces in HTML (harder to read during dev) | 5/10 |

Some settings to consider when using Glasslt-VSC extension that I personally like to change in **settings.json**
```json

  "glassit.alpha": 240,
  "workbench.colorCustomizations": {
    "tab.activeBackground": "#4d0057",
    "tab.activeForeground": "#ffffff", 
    "editor.background": "#020202",
    "editorGutter.background": "#0000003f",
    "terminal.background": "#0c0c0c",
    "panel.background": "#0c0c0c"
  },
  "editor.scrollbar.verticalScrollbarSize": 30,
  "editor.minimap.enabled": false,

```

Other that might be of interest in general:
```json

  "editor.tabSize": 4,
  "editor.formatOnSave": true,
  "files.autoSave": "onFocusChange",

```

## _For C#_

| Extension | Author | Marketplace | For | Comments | MyStars |
| ------ | ------ | ------ | ------ | ------ | ------ |
| Omnisharp | Microsoft | [link](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp) | Several feautures | Set Use Modern Net feature for build for .NET 6 | 10/10 |
| Visual Studio IntelliCode | Microsoft | [link](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode) | AI-assisted development for Python, TypeScript/JavaScript and Java | Not for C# ? | 0/10 |
| C# Extensions | JosKreativ | [link](https://marketplace.visualstudio.com/items?itemName=kreativ-software.csharpextensions) | Add class from IDE | New files use old syntax (bracket namespaces) | 7/10 |

Some settings to consider when using JosKreativ extension that I personally like to change in **settings.json**

```json
  "csharpextensions.privateMemberPrefix": "_",
  "csharpextensions.useThisForCtorAssignments": false,
```

## _For SQLite_

| Extension | Author | Marketplace | For | Comments | MyStars |
| ------ | ------ | ------ | ------ | ------ | ------ |
| SQLite | alexcvzz |  |  |  |  |

## _For Microsoft SQL Server_

| Extension | Author | Marketplace | For | Comments | MyStars |
| ------ | ------ | ------ | ------ | ------ | ------ |
| SQL Server (mssql) | Microsoft |  |  |  |  |
| SQL Database Projects | Microsoft |  |  |  |  |


## HTML and CSS

| Extension | Author | Marketplace | For | Comments | MyStars |
| ------ | ------ | ------ | ------ | ------ | ------ |
| Live Server | Ritwick Dey |  | Launch your webapp from vscode with a click | Almost mandatory | 10/10 |
| HTML CSS Suport | ecmel |  |  |  |  |
| IntelliSense for CSS class names in HTML | Zignd | [link](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion) | Your CSS classes will appear in your HTML as suggestions |  | 10/10 |
| Auto Rename Tag | Jun Han |  | Update open/closing tag automatically | ALREADY INCLUDED IN VSCODE | 10/10 |
| Color Highlight | Sergii Naumov |  | Nice for CSS files to preview colors #fff in the editor |  | 8/10 |
| Image preview | Kiss Tamás | Preview images in HTML code editor |  |  | 10/10 |


## Tailwind

| Extension | Author | Marketplace | For | Comments | MyStars |
| ------ | ------ | ------ | ------ | ------ | ------ |
| Tailwind CSS IntelliSense | Tailwind Labs | [link](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) |  |  |  |  |

## SCSS

| Extension | Author | Marketplace | For | Comments | MyStars |
| ------ | ------ | ------ | ------ | ------ | ------ |
| Live Sass Compiler | Ritwick Dey |  |  |  |  |


## Javascript

| Extension | Author | Marketplace | For | Comments | MyStars |
| ------ | ------ | ------ | ------ | ------ | ------ |
| npm Intellisense | Christian Kohler |  |  |  |  |

## Angular

Autocompletion of imports works out of the box in VS Code. 

| Extension | Author | Marketplace | For | Comments | MyStars |
| ------ | ------ | ------ | ------ | ------ | ------ |
| Angular Language Service | Angular | [link](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template) | Add basic intellisense for HTML | Recognizes keyworks (ngFor, async) and code-behind variables | 8/10 |
| VSCode simple Icons with Angular | davidbabel | [link](https://marketplace.visualstudio.com/items?itemName=davidbabel.vscode-simpler-icons) | Icons for Angular | Helps a lot distinguishing files (services, modules, etc.) | 10/10 |
| Angular Snippets (Version 12) | John Papa |  |  |  |  |
| angular2-inline | Nate Wallace |  | Syntax highlight of inline HTML and CSS (in code behind) |  |  |
| Bracket Pair Colorizer 2 | CoenraadS |  |  | Good in Angular since almost anywhere you end up with nested brackets |  |
| C# to TypeScript | Adrian Wilczynski |  |  |  |  |
