<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7qx85bwi.css';
import '../../css/e/ewkztrbus.css';
import '../../css/x/x4pwz20fz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g7qx85bwi"/><path class="ewkztrbus"/><path class="x4pwz20fz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-x-20-bold" {...props}></Icon>
