## CNN-U-net-radio-image-reconstruction
 This repository contains exploratory experiments on beam-aware ML-assisted radio interferometric image reconstruction using simulated datasets and PyTorch-based architectures. The work involved iterative experimentation, scientific evaluation, and AI-assisted rapid prototyping. The project investigates compact-source recovery, flux conservation, and residual sidelobe artifacts in CNN/U-Net-based reconstruction frameworks using dirty-image and dirty-beam inputs.

## Method summary 

Sky model --> uv sampling --> Dirty image + dirty beam --> Beam-aware U-Net --> Reconstructed image --> Residual diagnostics


 ## Current limitations

- Training currently uses simplified simulated compact-source skies.
- uv sampling is still idealized compared to realistic interferometer tracks.
- Residual sidelobe-like artifacts remain challenging.
- Cross-interferometer generalization has not yet been explored.

## Future directions
- realistic uv tracks.
- visibility-domain learning.
- telescope-conditioned training.
- uncertainty estimation.
- beam-aware artifact suppression.

