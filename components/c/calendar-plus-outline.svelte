<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su5y6qvyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="su5y6qvyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-plus-outline" {...props}></Icon>
