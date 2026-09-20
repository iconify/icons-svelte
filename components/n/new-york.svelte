<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z22cmu4ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z22cmu4ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:new-york" {...props}></Icon>
