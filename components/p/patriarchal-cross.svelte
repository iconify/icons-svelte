<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0l-2y22w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m0l-2y22w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:patriarchal-cross" {...props}></Icon>
