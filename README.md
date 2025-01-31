# 4-digit NACA airfoil generator - directly to .stl - python

Script which directly generate 4-digit NACA profile to .STL file in ASCII code. 

![Preview](https://github.com/MiroslavKabat/pythonNacaProfileGeneratorSTL/blob/master/samples/Preview.png)

## Fast start - How to use this project:

* [Youtube](https://youtu.be/6W2zwtiZeJc) - How to simply run this script

## Preview

* [NACA 8408 - long wing](https://github.com/MiroslavKabat/pythonNacaProfileGeneratorSTL/blob/master/samples/naca8408_long.stl)
* [NACA 0012 - angle of attack 20°](https://github.com/MiroslavKabat/pythonNacaProfileGeneratorSTL/blob/master/samples/naca0012_angleOfAttack20.stl)
* [NACA 2412 - fine mesh](https://github.com/MiroslavKabat/pythonNacaProfileGeneratorSTL/blob/master/samples/naca2412_fineMesh.stl)

## Getting Started

You can simply run a script in Windows cmd or Ubuntu Bash.

Variables:
* "foil" - 4-digit NACA identifier
* "numberOfPoints" - cnt
* "length" - meter
* "chordLength" - meter
* "angleOfAttack" - deg

Example:
```
python myNaca.py 2412 150 1 3 6
```

or for default

```
python myNaca.py
```

### Prerequisites

Script works with Python 3.x.x

* [Python](https://www.python.org/) - Download link to latest Python

Tested in Windows 10 Pro and Ubuntu 16.04 with Python 3.6.5

## Authors

* **Miroslav Kabát**
* [www.miroslavkabat.cz](http://www.miroslavkabat.cz)
* +420 607 624 470
* kabat@keng.cz

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

Permissions
* Commercial use 
* Modification 
* Distribution 
* Private use 

Limitations
* Liability 
* Warranty 

## Next steps?

I hope in more free time to improve this script. 5-digit NACA will be next step.
