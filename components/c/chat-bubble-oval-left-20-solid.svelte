<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg5t6pbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lg5t6pbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-oval-left-20-solid" {...props}></Icon>
