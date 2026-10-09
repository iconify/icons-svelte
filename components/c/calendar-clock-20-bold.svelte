<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5wmwdblu.css';
import '../../css/k/kvqjz7b_z.css';
import '../../css/u/udpsv_2mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r5wmwdblu"/><path class="kvqjz7b_z"/><path class="udpsv_2mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-clock-20-bold" {...props}></Icon>
