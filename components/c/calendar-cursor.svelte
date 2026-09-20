<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxh-lfu2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxh-lfu2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-cursor" {...props}></Icon>
