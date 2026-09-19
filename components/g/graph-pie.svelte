<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvgtklzub.css';
import '../../css/r/rcy948b8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="wvgtklzub"/><path class="rcy948b8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:graph-pie" {...props}></Icon>
