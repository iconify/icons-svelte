<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph19vw9nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ph19vw9nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:ligature" {...props}></Icon>
