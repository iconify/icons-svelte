<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qapojybjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qapojybjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-week-begin" {...props}></Icon>
