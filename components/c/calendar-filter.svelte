<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw0pxcbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pw0pxcbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-filter" {...props}></Icon>
