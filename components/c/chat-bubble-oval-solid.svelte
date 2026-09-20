<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxd4tpyqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uxd4tpyqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-bubble-oval-solid" {...props}></Icon>
