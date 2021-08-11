# Citations for the WRENCH framework

In this repository, we keep an YAML file (`_data/citations.yml`), which contains a
list of references for the WRENCH framework (e.g., papers, articles, etc.).

We collect references for the [WRENCH website](https://wrench-project.org) and
the following papers:

```
@article{wrench2020fgcs,
  title = {Developing Accurate and Scalable Simulators of Production Workflow Management Systems with WRENCH},
  author = {Casanova, Henri and Ferreira da Silva, Rafael and Tanaka, Ryan and Pandey, Suraj and Jethwani, Gautam and Koch, William and Albrecht, Spencer and Oeth, James and Suter, Fr\'{e}d\'{e}ric},
  journal = {Future Generation Computer Systems},
  volume = {112},
  number = {},
  pages = {162--175},
  year = {2020},
  doi = {10.1016/j.future.2020.05.030}
}

@inproceedings{wrench2018works,
  title = {WRENCH: A Framework for Simulating Workflow Management Systems},
  author = {Casanova, Henri and Pandey, Suraj and Oeth, James and Tanaka, Ryan and Suter, Frederic and Ferreira da Silva, Rafael},
  booktitle = {13th Workshop on Workflows in Support of Large-Scale Science (WORKS'18)},
  year = {2018},
  pages = {74--85},
  doi = {10.1109/WORKS.2018.00013}
}
```

### Fields in the YAML file

| Field | Description |
| --- | --- |
| `year` | Publication year |
| `type` | Publication type (e.g., workshop, conference, thesis, presentation, etc.) | 
| `title` | Publication title |
| `authors` | Publication authors |
| `url` | Publication URL (preferrably DOI) |
| `self` | Whether the publication was done by the WRENCH team |
| `usage` | Whether the publication used WRENCH |
