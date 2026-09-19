<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dej4cza_d.css';
import '../../css/d/d2e0hniif.css';
import '../../css/o/on4mi1mmc.css';
import '../../css/s/smvgl5sak.css';
import '../../css/t/tp4a94b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="dej4cza_d"/><path clip-rule="evenodd" class="d2e0hniif"/><path class="on4mi1mmc"/><path class="smvgl5sak"/><path class="tp4a94b_n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:grin-beam-sweat" {...props}></Icon>
