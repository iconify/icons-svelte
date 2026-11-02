<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pchas7bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pchas7bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bubble-line" {...props}></Icon>
