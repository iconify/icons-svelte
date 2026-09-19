<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/u/u8_ot7bnm.css';
import '../../css/b/b7u9enlhv.css';
import '../../css/c/c6-vowhzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="u8_ot7bnm"/><path class="b7u9enlhv"/><path class="c6-vowhzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:layer-backward" {...props}></Icon>
