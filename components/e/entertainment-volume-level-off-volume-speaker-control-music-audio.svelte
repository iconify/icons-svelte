<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7yby9bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="m7yby9bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:entertainment-volume-level-off-volume-speaker-control-music-audio" {...props}></Icon>
