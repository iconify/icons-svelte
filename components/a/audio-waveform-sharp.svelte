<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag9jxsbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ag9jxsbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:audio-waveform-sharp" {...props}></Icon>
