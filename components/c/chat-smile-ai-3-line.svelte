<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo1mgl7xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo1mgl7xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-smile-ai-3-line" {...props}></Icon>
