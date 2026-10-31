<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws_06cpxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws_06cpxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-circle-close-fill-round" {...props}></Icon>
