<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7x_w-bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x7x_w-bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:campground" {...props}></Icon>
