<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8jxl3bzb.css';
import '../../css/b/bqmve1p5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="w8jxl3bzb"/><path class="bqmve1p5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:heavy-dollar-sign" {...props}></Icon>
