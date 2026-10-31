<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzn4wdozi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzn4wdozi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-sparkle-round" {...props}></Icon>
