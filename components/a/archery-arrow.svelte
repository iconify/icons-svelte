<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k292zdxcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k292zdxcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:archery-arrow" {...props}></Icon>
