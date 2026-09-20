<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e63dy304p.css';
import '../../css/s/svi8x9byo.css';
import '../../css/c/cgkpg5bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e63dy304p"/><path class="svi8x9byo"/><path clip-rule="evenodd" class="cgkpg5bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-locked-fill" {...props}></Icon>
