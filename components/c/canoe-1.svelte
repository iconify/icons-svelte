<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/g/gci1exbgs.css';
import '../../css/c/cc9jmybaq.css';
import '../../css/n/n_7ow22tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="gci1exbgs"/><path class="cc9jmybaq"/><path class="n_7ow22tr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:canoe-1" {...props}></Icon>
