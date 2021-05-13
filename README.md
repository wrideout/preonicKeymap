# Preonic Keymap

## Overview
This repository contains a copy of the custom keymaps and layers I install on my OLKB Preonic keyboard.  Each of the six keymap layers I use has it's own special purpose.  To see the entire keymap layer assignments, see the PDF file contained in this repository.  Highlights of each layer are as follows:

### Layer 0: No Modifier
Layer 0 contains the "standard" keymap layout, where for the most part each key does what the keycap legend indicates.  The one exception to this is the ESC key, which functions as ESC if tapped, and a CTRL key if pressed and held.  No modifier is needed to enter this layer, as this is the default layer.  A few unorthodox key positions do exist here, as Layer 0 includes a dedicated F1 key in the upper left corner for iTerm2 hotkey use, pipe and backtick in positions mimicing the HHKB, and a split-spacebar layout for space and backspace access.

### Layer 1: FN
This layer remaps the entire top row of keys to be F1 through F12.  Other notable differences from the default layer include Vim-like movement for the H, J, K,  and L keys.  The keys Y, U, I, and O are remapped to Home, PageUp, PageDown, and End as well.  In this layer, pressing the SHIFT key toggles CAPS-LOCK.  This layer is entered by pressing and holding the FN key.

### Layer 2: LWR
This layer primarily serves to add media control to the arrow keys, as well as easy access to some coding symbols.  The spacebar invokes Play/Pause, LArrow brings back the previous track, RArrow brings up the next track, and the Up and Down arrows contol volume.  This layer is ented by pressing and holding the LWR key.

### Layer 3: RSE
This layer provides more access to symbols commonly used in coding, as well as an alternative way to invoke CAPS-LOCK, as well as Home, PageUp, PageDown, and End.  This layer is entered by pressing and holding the RSE key.

### Layer 4: RSE+LWR
This layer provides access to actions unique to the Preonic's firmware and PCB, such as PCB Reset which is useful when flashing new firmwares.  This layer also provides a handy way to sleep the system to which the Preonic is connected, via the ESC key.  This layer is ented by pressing and holding the RSE and LWR keys simultaneously.  

### Layer LWR+FN
This layer enables a full keypad in the upper-corder of the Preonic, and is entered by pressing and holding the LWR and FN keys simultaneously.

## Using These Files
The JSON file contained in this repository is meant to be used to load the firmware for editing on with the [QMK Confiurator](https://config.qmk.fm/).  The PDF is meant to be a reference when learning the layers summarized above.  The BIN file is the actual firmware file, compiled via the QMK Configuration, and should be loaded onto the Preonic with the [OMK Toolbox](https://beta.docs.qmk.fm/tutorial/newbs_flashing) app.
