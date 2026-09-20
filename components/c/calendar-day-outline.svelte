<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iegxcwbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iegxcwbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-day-outline" {...props}></Icon>
