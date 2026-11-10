# refseq39 — MITOS2 reference data (RefSeq 39 Metazoa (MITOS1's reference set))

A mirror of `refseq39.tar.bz2` from the MITOS2 reference data, Zenodo record
[4284483](https://zenodo.org/records/4284483) (doi:[10.5281/zenodo.4284483](https://doi.org/10.5281/zenodo.4284483)),
byte for byte (md5 `43182efaaa298691d5e9160f2f3e8c85`, the same as Zenodo's). It is mirrored here only because Zenodo throttles
downloads; MitOmics downloads it from this repository and falls back to Zenodo.

    wget https://raw.githubusercontent.com/zampini28/refseq39/refs/heads/main/refseq39.tar.bz2
    echo "43182efaaa298691d5e9160f2f3e8c85  refseq39.tar.bz2" | md5sum -c -
    tar xjf refseq39.tar.bz2          # -> refseq39/, used as: runmitos ... -r refseq39 -R .

**Authors:** Matthias Bernt, Frank Jühling, Alexander Donath, Abdullah H. Sahyoun, Manja Marz,
Peter F. Stadler, Martin Middendorf. *Reference data for MITOS2.* Zenodo (2020).

**License:** [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by-4.0/),
as published on Zenodo. Unmodified.
