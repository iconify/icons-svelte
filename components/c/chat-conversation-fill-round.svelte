<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8uoaj-wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8uoaj-wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-conversation-fill-round" {...props}></Icon>
