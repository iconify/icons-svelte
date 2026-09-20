<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/salf2bcen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="salf2bcen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rhode-island-with-capital-star" {...props}></Icon>
