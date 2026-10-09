<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-wcb8bfh.css';
import '../../css/i/iuu9occ8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a-wcb8bfh"/><path class="iuu9occ8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-price-20-bold" {...props}></Icon>
