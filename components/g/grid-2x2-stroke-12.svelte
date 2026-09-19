<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0uoc3w9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="y0uoc3w9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:grid-2x2-stroke-12" {...props}></Icon>
