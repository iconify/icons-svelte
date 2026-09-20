<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owsm1-kve.css';
import '../../css/b/b1rupy8li.css';
import '../../css/y/ybmkcumuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="owsm1-kve"/><path class="b1rupy8li"/><path class="ybmkcumuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:business-products-performance-money-increase" {...props}></Icon>
