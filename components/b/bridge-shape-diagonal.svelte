<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgcwbvbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rgcwbvbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bridge-shape-diagonal" {...props}></Icon>
