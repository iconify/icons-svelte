<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy_9vu8he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="jy_9vu8he"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mail-send-reply-email-reply-message-actions-action-arrow" {...props}></Icon>
