<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7sz9-bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7sz9-bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:music-note-solid" {...props}></Icon>
