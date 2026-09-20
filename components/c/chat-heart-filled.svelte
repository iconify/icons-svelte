<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a48vx3ehj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a48vx3ehj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-heart-filled" {...props}></Icon>
