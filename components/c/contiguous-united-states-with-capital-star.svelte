<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b16somc0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b16somc0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:contiguous-united-states-with-capital-star" {...props}></Icon>
