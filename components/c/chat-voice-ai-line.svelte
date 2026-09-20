<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6wl17_vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6wl17_vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-voice-ai-line" {...props}></Icon>
