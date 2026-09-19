<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/e/efh70xbdi.css';
import '../../css/h/hk9y0zedv.css';
import '../../css/i/i0_oy7bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="efh70xbdi"/><path class="hk9y0zedv"/><path class="i0_oy7bap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:dice" {...props}></Icon>
