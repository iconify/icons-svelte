<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xacu3z89s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xacu3z89s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-smile-ai-line" {...props}></Icon>
