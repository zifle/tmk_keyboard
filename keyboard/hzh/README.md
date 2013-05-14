HZH keyboard firmware
======================


## Build
Move to this directory then just run `make` like:

   $ make -f Makfile.[pjrc|lufa]

Use `Makefile.pjrc` if you want to use PJRC stack or use `Makefile.lufa` for LUFA stack.


## Boot Magic
Plugin pressing these `Boot Magic` key.

- `Fn` key for bootloader kick up.
- `D` key for Debug enable.


## Keymap
One version of keymap is available. `HZH`(default).
See keymap.c to define your own favourite keymap.

    $ make -f Makefile.[pjrc|lufa] [keymap name]


### 3. HZH keymap
This is my keymap(default) with a close to HHKB, default layout.

See [keymap.c](keymap.c) for detail.

#### 3.0 HZH Default Layer
    ,-----------------------------------------------------------.
    |Esc|  1|  2|  3|  4|  5|  6|  7|  8|  9|  0|  -|  =| `| Bsp|
    |-----------------------------------------------------------|
    |Tab  |  Q|  W|  E|  R|  T|  Y|  U|  I|  O|  P|  [|  ]|   \ |
    |-----------------------------------------------------------|
    |LCTRL |  A|  S|  D|  F|  G|  H|  J|  K|  L|  ;|  '| Return |
    |-----------------------------------------------------------|
    |Shift   |  Z|  X|  C|  V|  B|  N|  M|  ,|  .|  /|Shift |*L1|
    `--------------------------------------------------,--------'
           |Alt|Gui |        Space            |CTRL|Alt|
           `-------------------------------------------'

#### 3.1 HZH fn-layer
    ,-----------------------------------------------------------.
    |  `| F1| F2| F3| F4| F5| F6| F7| F8| F9|F10|F11|F12|   |Del|
    |-----------------------------------------------------------|
    |     |Mut|VoU|P/P|   |   |   |   |Psc|   |   |Up |   |Inser|
    |-----------------------------------------------------------|
    |      |Prv|VoD|Nxt|   |   |  *|  /|Hom|PgU|Lef|Rig|        |
    |-----------------------------------------------------------|
    |        |   |   |   |   |   |  +|  -|End|PgD|Dow|      |*L0|
    `---------------------------------------------------,-------'
           |   |    |     Play/Pause           |    |   |
           `--------------------------------------------'
    
    Blank keys are transparent