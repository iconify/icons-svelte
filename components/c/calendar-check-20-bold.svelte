<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7qx85bwi.css';
import '../../css/s/sgp4cobry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g7qx85bwi"/><path class="sgp4cobry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-check-20-bold" {...props}></Icon>
