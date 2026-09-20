<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf413j1th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf413j1th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-2-ai-fill" {...props}></Icon>
