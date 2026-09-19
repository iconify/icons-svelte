<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkkxb-b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pkkxb-b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-bottom-center-text-20-solid" {...props}></Icon>
