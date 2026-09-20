<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r33v170sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r33v170sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-weekend-outline" {...props}></Icon>
