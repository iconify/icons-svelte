<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_xoy_top.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":650,"height":800};
const content = `<path class="p_xoy_top"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:market" {...props}></Icon>
