<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a__s2g6zp.css';
import '../../css/c/cd9wpgo-d.css';
import '../../css/i/ir2lu_bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="a__s2g6zp"><path class="cd9wpgo-d"/><path class="ir2lu_bgj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:crop-bold" {...props}></Icon>
