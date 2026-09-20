<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e51pr79qy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e51pr79qy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:calendar-schedule-line" {...props}></Icon>
