<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxng6ibct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxng6ibct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:ai-voice-sharp" {...props}></Icon>
