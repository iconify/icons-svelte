<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylwh1bc5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ylwh1bc5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-bottom-center-20-solid" {...props}></Icon>
