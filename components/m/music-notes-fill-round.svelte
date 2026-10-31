<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmxmc5hjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmxmc5hjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:music-notes-fill-round" {...props}></Icon>
