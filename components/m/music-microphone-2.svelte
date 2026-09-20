<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj_9mrpio.css';
import '../../css/t/te90vbbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fj_9mrpio"/><path class="te90vbbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:music-microphone-2" {...props}></Icon>
