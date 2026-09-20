<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpw-lplim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mpw-lplim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:chat-bubble-typing-oval" {...props}></Icon>
