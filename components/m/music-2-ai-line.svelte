<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfiksmb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfiksmb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:music-2-ai-line" {...props}></Icon>
