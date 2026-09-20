<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3w73pktn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="x3w73pktn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-voice-mail-off-mic-audio-mike-music-microphone-mute-off" {...props}></Icon>
