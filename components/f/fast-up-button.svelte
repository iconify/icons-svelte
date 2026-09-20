<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij2x_72vy.css';
import '../../css/f/f-f4m3bjf.css';
import '../../css/k/k_gz_fskv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<g class="ij2x_72vy"><path class="f-f4m3bjf"/><path class="k_gz_fskv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:fast-up-button" {...props}></Icon>
