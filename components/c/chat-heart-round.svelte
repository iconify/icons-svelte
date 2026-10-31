<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkpkt12ai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkpkt12ai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-heart-round" {...props}></Icon>
