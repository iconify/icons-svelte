<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag57fwbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ag57fwbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:north-star-16" {...props}></Icon>
