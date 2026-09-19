<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc3c8rbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dc3c8rbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:bookmarks" {...props}></Icon>
