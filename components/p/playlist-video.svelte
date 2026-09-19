<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a71b_4pwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a71b_4pwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:playlist-video" {...props}></Icon>
