<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/w/whd865izb.css';
import '../../css/n/nj6gqjb-d.css';
import '../../css/h/h-wpcv3yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="whd865izb"/><path class="nj6gqjb-d"/><path class="h-wpcv3yo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:newspaper" {...props}></Icon>
