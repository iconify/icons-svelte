<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hov0yh0oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hov0yh0oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-two-bubbles-oval-remix" {...props}></Icon>
