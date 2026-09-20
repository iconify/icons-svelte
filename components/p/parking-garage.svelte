<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kemzep4yh.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/d/de0lnx-3x.css';
import '../../css/t/tp7_yl3-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="kemzep4yh"/><g class="ij2x_72vy"><path class="de0lnx-3x"/><path class="tp7_yl3-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:parking-garage" {...props}></Icon>
