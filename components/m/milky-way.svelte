<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ee45ycbzu.css';
import '../../css/t/t0j7g2fur.css';
import '../../css/i/iqg45ybon.css';
import '../../css/t/ttm2n_87g.css';
import '../../css/c/cvyeblbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ee45ycbzu"/><path class="t0j7g2fur"/><path class="iqg45ybon"/><path class="ttm2n_87g"/><path clip-rule="evenodd" class="cvyeblbsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:milky-way" {...props}></Icon>
