<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8bdsc6ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o8bdsc6ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-bubble-oval-notification-solid" {...props}></Icon>
