<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iysf4jv4i.css';
import '../../css/l/lrx_ag2ld.css';
import '../../css/u/u7alcxwrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="iysf4jv4i"/><path class="lrx_ag2ld"/><path class="u7alcxwrl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:crosshairs" {...props}></Icon>
