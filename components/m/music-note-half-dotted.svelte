<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhjc9obbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhjc9obbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-note-half-dotted" {...props}></Icon>
