<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhm60xclg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qhm60xclg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:entertainment-volume-level-low-volume-speaker-lower-down-control-music-low-audio" {...props}></Icon>
