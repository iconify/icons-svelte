<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_k4pac1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_k4pac1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-1-ai-line" {...props}></Icon>
