<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7z7izt0q.css';
import '../../css/m/mvvtxab3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="p7z7izt0q"/><path class="mvvtxab3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-microsoft-teams" {...props}></Icon>
