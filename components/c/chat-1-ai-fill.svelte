<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-ch-u9hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-ch-u9hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-1-ai-fill" {...props}></Icon>
