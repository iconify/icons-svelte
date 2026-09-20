<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vzo3ypbps.css';
import '../../css/o/oi9ky1bdz.css';
import '../../css/x/x43s2zn6y.css';
import '../../css/p/pfllnjb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="vzo3ypbps"/><path class="oi9ky1bdz"/><path class="x43s2zn6y"/><path class="pfllnjb4h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alarm-play-linear" {...props}></Icon>
