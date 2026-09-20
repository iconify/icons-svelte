<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmf0a8bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmf0a8bvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-voice-line" {...props}></Icon>
