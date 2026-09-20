<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7ibatb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i7ibatb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:heatmap" {...props}></Icon>
