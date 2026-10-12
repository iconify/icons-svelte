<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5wmwdblu.css';
import '../../css/k/kvqjz7b_z.css';
import '../../css/h/hayl1lfmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r5wmwdblu"/><path class="kvqjz7b_z"/><path class="hayl1lfmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-minus-20-bold" {...props}></Icon>
