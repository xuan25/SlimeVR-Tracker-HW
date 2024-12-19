# SlimeVR-Tracker-HW by Xuan25

A design of SlimeVR Tracker by Xuan25

## Features

- 3D printed case
- 2-layer PCB
- firmware uploading via USB
- 9-hour durability with 700mAh 803030 Li-Po battery
- Dimension: 55mm (l) x 37mm (w) x 23mm (h)
- Optimized for hand soldering, with enough spacing to comfortably handle 0603 SMD components and maintain adequate clearance.

## Preview

![case-a.png](./imgs/case-a.png)
![case-b.png](./imgs/case-b.png)
![pcb-3d.png](./imgs/pcb-3d.png)
![pcb-a.png](./imgs/pcb-a.png)
![pcb-b.png](./imgs/pcb-b.png)
![build.png](./imgs/build.png)

## Please note: Before you send the case model to your 3D printer

**You may want to update the following parameters in the Case design Spreadsheet to match the performance of your 3D printer and material.**

- **Tol**: Adjusts the clearance between mating parts. Increase this value if your 3D printer cannot achieve tight tolerances, ensuring the parts fit together properly despite limited printing accuracy.
- **SnapFitNotchWidth**: Controls the depth of the snap-fit notch. A larger value can provide a more robust snap-fit connection but requires the material to have better toughness.
  - Plastics are usually stronger than resin, so you should consider to use a lower value.
- **BaseMargin**: Controls the margin of the base. Since the snap-fit will catch on the base’s margin, a smaller margin requires the material to have sufficient strength to ensure a reliable snap-fit connection.
  - Resin are usually softer than plastics, so you should consider to use a greater value.
