<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1hccg7-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1hccg7-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-4-bold" {...props}></Icon>
