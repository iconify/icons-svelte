<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u5a8z1bvb.css';
import '../../css/r/r2yb3pnfd.css';
import '../../css/c/cupeqiojs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u5a8z1bvb"/><path class="r2yb3pnfd"/><path class="cupeqiojs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-star-line-duotone" {...props}></Icon>
