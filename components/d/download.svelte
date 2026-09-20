<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wvc8_zo-w.css';
import '../../css/u/us_lcey2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="wvc8_zo-w"/><path class="us_lcey2a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:download" {...props}></Icon>
