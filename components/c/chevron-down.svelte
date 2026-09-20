<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8jy1y7cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="u8jy1y7cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:chevron-down" {...props}></Icon>
