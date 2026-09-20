<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vof2l4cbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vof2l4cbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:music-note-off-1-remix" {...props}></Icon>
