<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxce8tbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="oxce8tbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:entertainment-volume-down-speaker-down-volume-control-audio-music-decrease" {...props}></Icon>
