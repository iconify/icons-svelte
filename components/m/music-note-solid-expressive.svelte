<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl1yt9bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl1yt9bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:music-note-solid-expressive" {...props}></Icon>
