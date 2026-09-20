<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep5jz7ppd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ep5jz7ppd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-filter" {...props}></Icon>
