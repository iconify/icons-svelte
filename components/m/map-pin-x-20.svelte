<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6ztyxb8m.css';
import '../../css/y/yswetvbum.css';
import '../../css/e/ed4mxccbx.css';
import '../../css/e/eqdr87b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e6ztyxb8m"/><path class="yswetvbum"/><path class="ed4mxccbx"/><path class="eqdr87b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-pin-x-20" {...props}></Icon>
