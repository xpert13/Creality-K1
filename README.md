# Creality K1
My files for Creality K1 printer

## Useful links:

- [Creality K1 root script](https://guilouz.github.io/Creality-K1-Series/)
- [Klipper update](https://github.com/K1-Klipper/installer_script_k1_and_max)
- [Anarhyst266's K1 configs](https://github.com/Anarhyst266/k1_conf)
- [Custom extruder](https://www.printables.com/model/669504-artis3d-feeder-type-mk-for-creality-k1k1max/collections)

## Using 2 pin fans

Look at the changes at 2pin-fans-mode branch

## Custom extruder useful info

After changes in printer.cfg you need to exclude 4 mm from printing bed area in a slicer. For OrcaSlicer you need to change "Excluded bed area" param to `0x0, 220x0, 220x4, 0x4`.
Also you need to calibrate [extruder rotation distance](https://3dua.info/tutorials/article/7-kalibrovka-ekstrudera-na-prodavleniy-plastik-klipper/).

## Known issues

### Selfcheck error:

If you want to make factory reset and your initial selfcheck would be faild - use [this instruction](https://store.creality.com/blog/creality-k1-max-skip-the-startup-self-check) to skip it.
