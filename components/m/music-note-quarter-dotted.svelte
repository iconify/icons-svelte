<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8g0t5nob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8g0t5nob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-note-quarter-dotted" {...props}></Icon>
