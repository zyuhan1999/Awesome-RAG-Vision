# Canonical catalog update for review

This patch is prepared against upstream commit 084df5cd9be15aeeecf74914341aa1a3254932d5 and adds/repairs FreeRet and Video-o3 (ICML 2026), TimeLens2 and VideoChat3 (arXiv 2026) in the supplied-video evidence scope.

The canonical JSON and README/CSV/BibTeX exports are synchronized. FreeRet's final nine-author PMLR list is preserved with verified publication-author evidence while retaining the older DBLP evidence. Existing catalog records and the fixed manuscript audit are retained.

Validation: seven source/author regression tests pass; all 179 records render and pass --check; the 15-file patch was checked against its exact base. The existing CI workflow is unchanged and is not included in the patch.

Download the patch and apply it to the recorded upstream base using git apply. The implementation commit validated locally is f703cd5c45d989a1a3a508a8abd332adf6dec0c6.

Prepared by Yuhan Zhu, a co-author of the four papers, with AI assistance.
