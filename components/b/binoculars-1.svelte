<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/m/mwei4gkkt.css';
import '../../css/d/du887ss5t.css';
import '../../css/n/nr9v46bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="mwei4gkkt"/><path class="du887ss5t"/><path class="nr9v46bny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:binoculars-1" {...props}></Icon>
