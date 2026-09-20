<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9eu5vbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d9eu5vbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-write-2" {...props}></Icon>
