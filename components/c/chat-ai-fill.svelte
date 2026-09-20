<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad3tqwbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad3tqwbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-ai-fill" {...props}></Icon>
