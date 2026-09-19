<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/ra_dfpp6b.css';
import '../../css/z/zdg6l3u0q.css';
import '../../css/m/mzej6wbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ra_dfpp6b"/><path class="zdg6l3u0q"/><path class="mzej6wbap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:map" {...props}></Icon>
