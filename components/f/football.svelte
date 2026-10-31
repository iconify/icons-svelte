<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/u/u5pzwml9t.css';
import '../../css/i/iieh6_xpy.css';
import '../../css/i/i4uh5terb.css';
import '../../css/i/ijfpbushk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="u5pzwml9t wm-shadow"/><path class="iieh6_xpy wm-shadow"/><path class="i4uh5terb"/><path class="ijfpbushk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:football" {...props}></Icon>
