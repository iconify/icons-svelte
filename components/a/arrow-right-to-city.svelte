<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7qbhwd3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="r7qbhwd3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-right-to-city" {...props}></Icon>
