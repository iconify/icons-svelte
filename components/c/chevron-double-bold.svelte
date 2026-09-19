<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a__s2g6zp.css';
import '../../css/x/xo73r-1bv.css';
import '../../css/i/isuy6sbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="a__s2g6zp"><path class="xo73r-1bv"/><path class="isuy6sbwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:chevron-double-bold" {...props}></Icon>
