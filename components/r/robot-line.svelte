<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg346tbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg346tbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:robot-line" {...props}></Icon>
