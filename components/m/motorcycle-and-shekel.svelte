<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s02ruwbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s02ruwbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorcycle-and-shekel" {...props}></Icon>
