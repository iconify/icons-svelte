<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2pacqbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k2pacqbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:conifer-tree-with-star-and-ornaments" {...props}></Icon>
