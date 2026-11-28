<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvkprxd5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bvkprxd5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:music-notes-slash-light" {...props}></Icon>
