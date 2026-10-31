<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lezojdu3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lezojdu3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-conversation-circle-round" {...props}></Icon>
