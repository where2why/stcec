# STCEC

The Spatial-Temporal Change in Environmental Context (STCEC) is a dataset that can be used to explore environmental change over time. STCEC consists of 600 images, consisting of three timesteps of 200 sample patches (referred to as such for nomenclature purposes). Each patch contains 10-by-10 pixels. The 200 patches are split into four subgroups each containing 50 patches. The subgroups (and respective subdirectories) are

* Homogeneous with change: This subgroup contains patches with a single environmental class that changes over the time period. (./hoc)
* Homogeneous without change: This subgroup contains patches with a single environmental class that does not change over the time period. (./honc)
* Heterogeneous with change: This subgroup contains patches with multiple environmental classes that change over the time period. (./hec)
* Heterogeneous without change: This subgroup contains patches with contains multiple environmental classes that does not change over the time period. (./henc)

The three subdirectories under each directory refer to the timesteps (1,2 or 3).

STCEC was built using Landsat images and SLATS data.
