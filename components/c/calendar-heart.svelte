<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd8mj3bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd8mj3bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:calendar-heart" {...props}></Icon>
