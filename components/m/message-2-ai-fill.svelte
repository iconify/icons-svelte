<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5vkv6bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5vkv6bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-2-ai-fill" {...props}></Icon>
