<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqfh6cbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jqfh6cbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-bubble-oval-notification-remix" {...props}></Icon>
