<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py5592tpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="py5592tpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:file-media" {...props}></Icon>
