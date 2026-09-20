<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn95nbc_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="pn95nbc_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:entertainment-volume-off-speaker-music-mute-volume-control-audio-off-mute" {...props}></Icon>
