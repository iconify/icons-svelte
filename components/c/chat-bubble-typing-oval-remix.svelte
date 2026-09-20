<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcabsycft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pcabsycft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-bubble-typing-oval-remix" {...props}></Icon>
