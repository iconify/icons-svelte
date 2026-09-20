<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9dr1ubsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e9dr1ubsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:district-of-columbia-with-capital-star" {...props}></Icon>
