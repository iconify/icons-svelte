<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvzqwhbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvzqwhbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:disc-album-line" {...props}></Icon>
