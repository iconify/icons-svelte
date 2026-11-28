<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5ihe_5ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="k5ihe_5ob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:postage-stamp-bold" {...props}></Icon>
