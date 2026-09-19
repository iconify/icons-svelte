<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur_xiv5wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="ur_xiv5wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:comment-list" {...props}></Icon>
