<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm43ohb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm43ohb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:keyboard-music-sharp" {...props}></Icon>
