<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/k/ko6ce4blt.css';
import '../../css/w/w9xiptpes.css';
import '../../css/c/cgmljzbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ko6ce4blt"/><path class="w9xiptpes"/><path class="cgmljzbtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cogwheel" {...props}></Icon>
