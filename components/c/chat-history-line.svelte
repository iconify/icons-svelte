<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a55cl3b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a55cl3b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-history-line" {...props}></Icon>
