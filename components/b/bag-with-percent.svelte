<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz8egfbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jz8egfbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bag-with-percent" {...props}></Icon>
