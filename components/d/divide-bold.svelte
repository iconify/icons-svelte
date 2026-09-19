<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a__s2g6zp.css';
import '../../css/l/ln7cyvcfw.css';
import '../../css/z/z2xr0pb1c.css';
import '../../css/w/wpmk60uqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="a__s2g6zp"><path class="ln7cyvcfw"/><rect class="z2xr0pb1c"/><rect class="wpmk60uqr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:divide-bold" {...props}></Icon>
