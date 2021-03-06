---
title: "Exemplary Natural Images Explain CNN Activations Better than State-of-the-Art Feature Visualization"
type: ICLR 2021
collection: publications
permalink: /publication/2020-10-09-feature-visualization
excerpt: 'Using human psychophysical experiments, we show that natural images can be significantly more informative for interpreting neural network activations than synthetic feature visualizations.'
date: 2021-03-05
paperurl: 'https://openreview.net/forum?id=-vhO2VPjbVa'
paperurldescription: 'Access the  paper'
authors: 'Borowski\*, J., **Zimmermann\*, R. S.**, Schepers, J., Geirhos, R. , Wallis, T. S. A., Bethge, M. and Brendel, W.'
venue: 'NeurIPS 2020 Workshop: Shared Visual Representations in Human & Machine Intelligence'
citation: 'Borowski, J., Zimmermann, R. S., Schepers, J., Geirhos, R. , Wallis, T. S. A., Bethge, M. and Brendel, W., Natural images are more informative for interpreting CNN activations than synthetic feature visualizations .'
---
Feature visualizations such as synthetic maximally activating images are a widely used explanation method to better understand the information processing of convolutional neural networks (CNNs). At the same time, there are concerns that these visualizations might not accurately represent CNNs' inner workings. Here, we measure how much extremely activating images help humans to predict CNN activations.
Using a well-controlled psychophysical paradigm, we compare the informativeness of synthetic images by Olah et al. (2017) with a simple baseline visualization, namely exemplary natural images that also strongly activate a specific feature map. Given either synthetic or natural reference images, human participants choose which of two query images leads to strong positive activation. The experiment is designed to maximize participants' performance, and is the first to probe intermediate instead of final layer representations. We find that synthetic images indeed provide helpful information about feature map activations ($82\pm4\%$ accuracy; chance would be $50\%$). However, natural images - originally intended to be a baseline - outperform these synthetic images by a wide margin (92 ± 2%). Additionally, participants are faster and more confident for natural images, whereas subjective impressions about the interpretability of the feature visualizations by Olah et al. (2017) are mixed. The higher informativeness of natural images holds across most layers, for both expert and lay participants as well as for hand- and randomly-picked feature visualizations. Even if only a single reference image is given, synthetic images provide less information than natural images (65 ± 5% vs. 73 ± %). In summary, synthetic images from a popular feature visualization method are significantly less informative for assessing CNN activations than natural images. We argue that visualization methods should improve over this simple baseline.

[Download paper here](https://openreview.net/forum?id=QO9-y8also-)