<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbzootbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbzootbwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-blank" {...props}></Icon>
