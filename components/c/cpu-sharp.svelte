<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr2fe1bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rr2fe1bto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:cpu-sharp" {...props}></Icon>
