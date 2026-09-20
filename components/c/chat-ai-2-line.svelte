<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvm9cwbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvm9cwbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-ai-2-line" {...props}></Icon>
