<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-q1ywbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="f-q1ywbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:chat-bubble-text-square" {...props}></Icon>
