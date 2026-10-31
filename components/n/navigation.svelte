<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/r/rkx0dbdzu.css';
import '../../css/b/bp47hebjk.css';
import '../../css/c/cpo-sbv4q.css';
import '../../css/i/ir2ohlbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="rkx0dbdzu wm-shadow"/><path class="bp47hebjk wm-shadow"/><path class="cpo-sbv4q"/><path class="ir2ohlbyr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:navigation" {...props}></Icon>
