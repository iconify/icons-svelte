<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cflj2gbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cflj2gbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-voice-fill" {...props}></Icon>
