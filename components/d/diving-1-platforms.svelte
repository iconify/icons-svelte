<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz4z-d47e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oz4z-d47e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:diving-1-platforms" {...props}></Icon>
