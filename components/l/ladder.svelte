<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbcewlb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cbcewlb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:ladder" {...props}></Icon>
