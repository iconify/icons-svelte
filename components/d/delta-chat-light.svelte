<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyr5q_bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uyr5q_bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:delta-chat-light" {...props}></Icon>
