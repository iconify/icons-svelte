<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyn48u6gq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eyn48u6gq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-bubble-typing-oval-solid" {...props}></Icon>
