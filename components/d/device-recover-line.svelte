<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy9o1kbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wy9o1kbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:device-recover-line" {...props}></Icon>
