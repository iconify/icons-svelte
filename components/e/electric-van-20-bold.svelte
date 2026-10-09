<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3wfd7fjc.css';
import '../../css/c/ca1yglwsn.css';
import '../../css/u/ug_y5ht_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h3wfd7fjc"/><path class="ca1yglwsn"/><path class="ug_y5ht_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-van-20-bold" {...props}></Icon>
