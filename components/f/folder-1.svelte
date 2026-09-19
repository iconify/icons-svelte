<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/d/dkp5t5bjh.css';
import '../../css/h/hepxbzbrb.css';
import '../../css/l/l9tot5bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="dkp5t5bjh"/><path class="hepxbzbrb"/><path class="l9tot5bbd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:folder-1" {...props}></Icon>
