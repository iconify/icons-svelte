<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m03t3ybdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="m03t3ybdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:entertainment-control-button-pause-1-button-television-buttons-movies-tv-pause-video-controls" {...props}></Icon>
