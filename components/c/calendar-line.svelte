<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i51-s6bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i51-s6bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-line" {...props}></Icon>
