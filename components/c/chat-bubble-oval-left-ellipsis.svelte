<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inftcdmqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="inftcdmqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:chat-bubble-oval-left-ellipsis" {...props}></Icon>
