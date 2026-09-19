<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofpgi6bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ofpgi6bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:chat-bubble-left" {...props}></Icon>
