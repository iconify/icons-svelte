<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n57ybouyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n57ybouyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:chat-bubble-left" {...props}></Icon>
