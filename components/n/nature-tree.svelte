<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwb25ab6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uwb25ab6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:nature-tree" {...props}></Icon>
