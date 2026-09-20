<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa-vm9pwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pa-vm9pwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-square-call" {...props}></Icon>
