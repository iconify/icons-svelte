<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgrtvpd0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hgrtvpd0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:chat-bubble-left-ellipsis" {...props}></Icon>
