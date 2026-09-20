<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvgvcux-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvgvcux-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:audio-waveform" {...props}></Icon>
