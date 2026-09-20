<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv4kzimdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv4kzimdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-voice-ai-fill" {...props}></Icon>
