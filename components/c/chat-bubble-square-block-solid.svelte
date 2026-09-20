<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwn_nxbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pwn_nxbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-bubble-square-block-solid" {...props}></Icon>
