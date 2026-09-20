<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3tc17cay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i3tc17cay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-bubble-square-warning-solid" {...props}></Icon>
