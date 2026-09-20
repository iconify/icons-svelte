<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw72m4boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw72m4boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-note-plus" {...props}></Icon>
