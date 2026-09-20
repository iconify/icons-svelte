<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsohb8bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsohb8bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chat-sleep-outline" {...props}></Icon>
