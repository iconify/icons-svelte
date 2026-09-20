<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf823hmzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="jf823hmzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:entertainment-control-button-play-pause-button-television-buttons-movies-play-pause-video-controls" {...props}></Icon>
