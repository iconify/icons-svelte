<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoyi7uoos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uoyi7uoos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:conifer-tree-and-bench-on-ground" {...props}></Icon>
