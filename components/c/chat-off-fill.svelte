<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk8o7xbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk8o7xbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-off-fill" {...props}></Icon>
