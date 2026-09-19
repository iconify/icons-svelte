<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/p/pczwx_b9m.css';
import '../../css/i/ieuur3b8f.css';
import '../../css/e/e3091ubgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="pczwx_b9m"/><path class="ieuur3b8f"/><path class="e3091ubgm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:gift-1" {...props}></Icon>
