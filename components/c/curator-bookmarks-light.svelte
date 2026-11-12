<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5h_zua9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p5h_zua9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:curator-bookmarks-light" {...props}></Icon>
