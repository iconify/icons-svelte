<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcz575ggm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcz575ggm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-smile-2-line" {...props}></Icon>
