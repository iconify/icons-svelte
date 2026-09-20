<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk0bp2b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vk0bp2b6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:iowa-with-capital-star" {...props}></Icon>
