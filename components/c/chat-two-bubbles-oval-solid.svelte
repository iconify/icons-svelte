<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2qf4sbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u2qf4sbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-two-bubbles-oval-solid" {...props}></Icon>
