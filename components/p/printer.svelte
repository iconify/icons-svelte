<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/n/nvkf6i-4k.css';
import '../../css/j/jxae9p33p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="nvkf6i-4k"/><path class="jxae9p33p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:printer" {...props}></Icon>
