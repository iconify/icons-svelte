<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxvjzktfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sxvjzktfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:new-york-with-capital-star" {...props}></Icon>
