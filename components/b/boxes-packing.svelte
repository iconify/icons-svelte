<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybmao4abp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ybmao4abp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:boxes-packing" {...props}></Icon>
