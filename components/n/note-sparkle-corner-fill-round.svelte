<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhg5h_ghh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhg5h_ghh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-sparkle-corner-fill-round" {...props}></Icon>
