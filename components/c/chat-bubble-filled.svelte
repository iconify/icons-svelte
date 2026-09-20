<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6h7dht2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6h7dht2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-bubble-filled" {...props}></Icon>
