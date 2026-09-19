<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/m/mipampm5e.css';
import '../../css/b/bcsqw5n-n.css';
import '../../css/s/s5lscfbct.css';
import '../../css/s/s0gt0yp1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="mipampm5e"/><path class="bcsqw5n-n"/><path class="s5lscfbct"/><path class="s0gt0yp1q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heart-sparkles" {...props}></Icon>
