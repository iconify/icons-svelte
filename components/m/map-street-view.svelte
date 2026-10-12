<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bfhygtega.css';
import '../../css/c/crhp8vbpq.css';
import '../../css/a/aj8_1eb2f.css';
import '../../css/m/mh50g1f2p.css';
import '../../css/d/dp_cy5b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle transform="rotate(90 12 4.54)" class="bfhygtega"/><path class="crhp8vbpq"/><path class="aj8_1eb2f"/><path class="mh50g1f2p"/><path class="dp_cy5b7g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:map-street-view" {...props}></Icon>
