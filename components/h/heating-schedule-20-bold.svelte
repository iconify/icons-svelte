<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4zy9ybio.css';
import '../../css/g/gw-flvwxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m4zy9ybio"/><path class="gw-flvwxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heating-schedule-20-bold" {...props}></Icon>
