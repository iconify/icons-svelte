<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nohw-0bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nohw-0bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:rhombus-arrow-right-solid-solid" {...props}></Icon>
