<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emmbwibof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emmbwibof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-1-ai-fill" {...props}></Icon>
