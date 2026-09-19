<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6ngt0_3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y6ngt0_3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:italic-stroke-16" {...props}></Icon>
