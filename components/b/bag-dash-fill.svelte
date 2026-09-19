<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w655fbcvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w655fbcvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bag-dash-fill" {...props}></Icon>
