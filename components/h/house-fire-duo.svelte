<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i793flwcp.css';
import '../../css/u/uejg4q-3x.css';
import '../../css/v/vwqgwrb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="i793flwcp"/><path class="uejg4q-3x"/><path class="vwqgwrb7v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:house-fire-duo" {...props}></Icon>
