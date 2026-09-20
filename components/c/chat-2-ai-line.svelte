<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf6uh2ajn.css';
import '../../css/r/rco1lvblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf6uh2ajn"/><path class="rco1lvblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-2-ai-line" {...props}></Icon>
