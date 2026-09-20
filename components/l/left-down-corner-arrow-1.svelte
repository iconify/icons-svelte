<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-e4hr07v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p-e4hr07v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:left-down-corner-arrow-1" {...props}></Icon>
