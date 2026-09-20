<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alnugs8yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="alnugs8yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:new-hampshire-with-capital-star" {...props}></Icon>
