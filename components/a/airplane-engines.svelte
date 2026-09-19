<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyuiy0bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xyuiy0bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:airplane-engines" {...props}></Icon>
