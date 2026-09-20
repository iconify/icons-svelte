<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owgf6abpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="owgf6abpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mosque" {...props}></Icon>
