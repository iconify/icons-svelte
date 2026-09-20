<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx68gfb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lx68gfb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:conifer-tree-and-flower-and-mountain-snowcapped" {...props}></Icon>
