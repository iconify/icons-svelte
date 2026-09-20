<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvfd5l4bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvfd5l4bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:calendar-schedule-fill" {...props}></Icon>
