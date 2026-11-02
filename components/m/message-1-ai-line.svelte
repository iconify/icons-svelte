<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjz2s1uvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjz2s1uvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-1-ai-line" {...props}></Icon>
