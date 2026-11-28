<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsc0xs_ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsc0xs_ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pine-tree-star" {...props}></Icon>
