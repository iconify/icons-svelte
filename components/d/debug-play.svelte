<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g65pj_bpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g65pj_bpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:debug-play" {...props}></Icon>
