# EnderWinder

A tool for generating G-code to lay copper wire along custom 3D paths on Ender-style printers. Includes tension control and hardware for guiding the wire around custom forms.

**Early development** – features are experimental and incomplete.  
For active development and source code, see the [`development` branch](https://github.com/wgbowley/EnderWinder/tree/development).

---

## Goals

- Wind multi-layer coils with precision  
- Ensure consistent coil resistance and turn count  
- Easy setup and support for different wire diameters  

---

## Hardware Concept

<img src="images/armuture.jpg" alt="Hardware concept" width="500"/>

EnderWinder should be able to wind coils similar to these from the `prototype_v0` linear motor — but with improved accuracy, repeatability, and uniformity.
