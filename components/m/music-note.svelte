<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/y/yp2pgobra.css';
import '../../css/t/t2s1tmb8r.css';
import '../../css/w/wa95x5b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ufeehvblu"><path class="yp2pgobra"/><ellipse class="t2s1tmb8r"/><path class="wa95x5b1d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:music-note" {...props}></Icon>
