<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2r3z0b1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c2r3z0b1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-bubble-square-write-solid" {...props}></Icon>
