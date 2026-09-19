<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/k/kg0z_nz0n.css';
import '../../css/h/hq6medc3z.css';
import '../../css/e/e3paigb_o.css';
import '../../css/f/fyb61ow7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="kg0z_nz0n"/><path class="hq6medc3z"/><path class="e3paigb_o"/><path class="fyb61ow7b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:calendar-outline" {...props}></Icon>
