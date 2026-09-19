<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mj86nfbjt.css';
import '../../css/w/w9_t02b1j.css';
import '../../css/o/osqcjnb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="mj86nfbjt"/><path clip-rule="evenodd" class="w9_t02b1j"/><path class="osqcjnb_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:headphones-bold" {...props}></Icon>
