<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drvpwlbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="drvpwlbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:globe" {...props}></Icon>
