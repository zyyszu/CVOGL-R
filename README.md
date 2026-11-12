# CVOGL-R

Official dataset release for **CVOGL-R**, introduced in our CVPR 2026 Findings paper:

**From Horizontal to Rotated: Cross-View Object Geo-Localization with Orientation Awareness**  
Chenlin Fu, Ao Gong, Xingtao Ling, Yingying Zhu  
**[Paper (CVF Open Access)](https://openaccess.thecvf.com/content/CVPR2026F/html/Fu_From_Horizontal_to_Rotated_Cross-View_Object_Geo-Localization_with_Orientation_Awareness_CVPRF_2026_paper.html)**

CVOGL-R extends the original [CVOGL dataset](https://github.com/sunyuxi/DetGeo) with refined **rotated bounding box (RBox)** annotations for cross-view object geo-localization. It supports both **drone-to-satellite** and **ground-to-satellite** settings.

## Dataset Download

| Platform | Download |
| --- | --- |
| Google Drive | [CVOGL-R.zip](https://drive.google.com/file/d/14UQJKcPrZdfssl-z8UvyFsWqM_bh0m8N/view?usp=sharing) |
| Baidu Netdisk | [CVOGL-R.zip](https://pan.baidu.com/s/1BxzjwDagp1bNyfwEBJw9oA?pwd=znkh) (Access code: `znkh`) |

The RBox annotations used by our dataset loader are represented as four corner points: `(x1, y1, x2, y2, x3, y3, x4, y4)`.

## Citation

If you find CVOGL-R useful in your research, please cite our paper:

```bibtex
@InProceedings{Fu_2026_CVPR,
  author    = {Fu, Chenlin and Gong, Ao and Ling, Xingtao and Zhu, Yingying},
  title     = {From Horizontal to Rotated: Cross-View Object Geo-Localization with Orientation Awareness},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Findings},
  month     = {June},
  year      = {2026},
  pages     = {7101--7110}
}
```

## Acknowledgements

CVOGL-R is built upon the original [CVOGL dataset / DetGeo project](https://github.com/sunyuxi/DetGeo). We thank its authors for their contribution. Please also respect any applicable terms of the original dataset.
