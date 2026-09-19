<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i07ac8bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i07ac8bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:grid-2x2-stroke-16" {...props}></Icon>
