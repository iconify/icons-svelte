<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm_pr0vcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm_pr0vcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eraser-ai-fill" {...props}></Icon>
