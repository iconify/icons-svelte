<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d36ww1bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d36ww1bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:brush" {...props}></Icon>
