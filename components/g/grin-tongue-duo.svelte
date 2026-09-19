<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-ntwsbcy.css';
import '../../css/p/psjnp-bmx.css';
import '../../css/t/tt1j1pb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="f-ntwsbcy"/><path class="psjnp-bmx"/><path class="tt1j1pb5b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grin-tongue-duo" {...props}></Icon>
