---
id: Neovim MOC
aliases: []
tags: []
created: "2025-08-21"
evolved: "2025-08-21"
in:
  - "[[Maps]]"
related: []
up:
  - "[[Thinking Map]]"
  - "[[Programming MOC]]"
---
*"The grammar of Vim is what allows you to edit at the speed of thought."*

This is your central map for mastering Neovim. The goal isn't to memorize commands, but to become fluent in its language. By focusing on the core principles, you'll find yourself constructing complex commands without thinking.

I'll give you the first and most important principle to start with:

- **Modal Editing**: Understand that you are always in a specific "mode" with a purpose (Normal, Insert, Visual). This is the foundation. `[[Modal Editing]]`
- **Composability**: Learn the "grammar". Motions are the nouns, operators are the verbs. `d` (delete) is a verb, `iw` (inside word) is a noun. `d` + `iw` = `diw`. `[[The Grammar of Vim]]`

# My Neovim Knowledge Base

*This is where you'll link your atomic notes on specific commands.*

## Navigation
- [[% (moves between brackets)]]
- [[w (moves forward by word)]]
- [[b (moves back my word)]]
- [[ctrl + i (jump forward)]]
- [[ctrl + o (jump backwards)]]
- [[ma (saves current location into register)]]
## Editing 

- [[ciw (change inside word)]]
- [[diw (delete in word)]]
- [[== (fixes stuff)]]

### Key Concepts

*For bigger ideas and workflows.*
- [[Vim Text Objects]]
- [[Vim Registers]]
- 
