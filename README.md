# You'd Better Run!

This project lets you know if you can walk leisurely to catch the bus, or if you'd better run.

This is a screen that hangs on the wall by the door to at a glance see how much time you have to get to the bus stop.

![Image of the completed project hanging on the wall](https://github.com/youdbetterrun/.github/raw/main/profile/image.jpg)

This repository holds the 3D models and assembly instructions.
There are separate repositories for the PCB and firmware models.
- [Firmware](https://github.com/youdbetterrun/youdbetterrun-firmware): The code that runs on the microcontroller.
- [PCB](https://github.com/youdbetterrun/youdbetterrun-pcb): The design files for the printed circuit board.

## Bill Of Materials

| Item                   | Quantity | Source                                                                                                                             |
| ---------------------- | -------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| Picture Frame          |        1 | https://www.ikea.com/ca/en/p/roedalm-frame-oak-effect-10566390/ (It should be easy to adapt the 3D printing files for other sizes) |
| e-paper screen         |        1 | [GoodDisplay 5.83" GDEQ0583T31](https://www.good-display.com/product/444.html)                                                     |
| Spacer                 |        1 | 3D printed                                                                                                                         |
| Mounting Plate         |        1 | 3D printed                                                                                                                         |
| PCB                    |        1 | [sister repository](https://github.com/youdbetterrun/youdbetterrun-pcb)                                                            |
| M2x3mm heat set insert |        3 | https://cnckitchen.store/products/heat-set-insert-m2-x-3-100-pieces                                                                |
| M2x6mm BHCS            |        3 | Hardware store                                                                                                                     |
| M3x6mm FHCS            |        4 | Hardware store                                                                                                                     |
| M3 locking nut         |        4 | Hardware store                                                                                                                     |

## Assembly Instructions

The image below shows the exploded view of the assembly.

![Exploded view](./docs/exploded_view.png)

1. 3D print everything in the `./stl/` folder. I used white PLA. No supports necessary.
1. Add the 3 heat set inserts to the 3D-printed mounting plate.
1. Leave the glass in the picture frame, but take out the back panel and the paper.
1. Add the spacer into the picture frame, then add the e-paper screen behind it.
1. Screw the PCB onto the mounting plate using the 3 BHCS.
1. Take the clips out of the picture frame's original backing. Connect them to the 3D-printed mounting plate by inserting the FHCS from the other side and using the locking nuts.
1. Put the mounting plate into the picture frame. Slide the hooks into the walls of the picture frame, securing everything inside.
1. Plug in FFC cable.
