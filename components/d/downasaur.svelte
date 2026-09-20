<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffwufdbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffwufdbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:downasaur" {...props}></Icon>
