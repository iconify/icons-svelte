<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owuglzbel.css';
import '../../css/f/f0zfi2mjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="owuglzbel"/><path class="f0zfi2mjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:music-notes-music-2" {...props}></Icon>
