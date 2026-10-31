<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bttcv_vis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bttcv_vis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-download-round" {...props}></Icon>
