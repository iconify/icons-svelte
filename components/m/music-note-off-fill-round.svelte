<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnd2b7bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnd2b7bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:music-note-off-fill-round" {...props}></Icon>
