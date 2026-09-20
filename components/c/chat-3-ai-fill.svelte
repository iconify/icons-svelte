<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frpv9b9jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frpv9b9jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-3-ai-fill" {...props}></Icon>
