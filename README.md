# KeyFrameMimic: Humanoid Motion Tracking with Sparse Keyframe Previews and World-Model Waypoint Supervision

**Authors:** Hao Zhou\*, Yang Li, Lin Ma\* (\*Corresponding authors)

- **Project Page (GitHub Pages):** https://zhhwss.github.io/keyframemimic/
- **Technical Report (PDF):** [`assets/paper/keyframemimic-arxiv-v1.pdf`](assets/paper/keyframemimic-arxiv-v1.pdf)

## Highlights
- **Clean 40-Motion Tracking (30k):** Residual latent bridging with temporal smoothing improves timed keyframe success (TKS) from **80.01%** (Sparse-Base) to **81.63%** (vs. **70.90%** for Dense-Full).
- **Early Learning Acceleration (10k):** Training-only world-model waypoint supervision lifts 10k TKS from **22.91%** to **36.60%** and reaches **81.78%** at 30k with zero inference overhead.
- **Corrupted-Mid Robustness:** Under intermediate-frame perturbation with clean keyframes, Dense-Full drops **42.95 pp** zero-shot (**70.90% &rarr; 27.95%**) and degrades to **17.89%** under direct corrupted training, whereas KeyFrameMimic Bridge shifts by **&lt; 0.2 pp** on average zero-shot (**81.59% &rarr; 81.78%**) and achieves **79.77% &plusmn; 0.66%** under direct corrupted training.

## Enable GitHub Pages
In GitHub repository **Settings &rarr; Pages**, set **Source** to **Deploy from a branch**, select branch **`main`** and folder **`/ (root)`**, then save.
