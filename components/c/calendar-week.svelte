<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrjnjpbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="qrjnjpbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:calendar-week" {...props}></Icon>
