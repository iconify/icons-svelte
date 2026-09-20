<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a28b4nb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="a28b4nb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mail-chat-bubble-square-messages-message-bubble-chat-square" {...props}></Icon>
