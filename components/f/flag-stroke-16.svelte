<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl9_6mbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tl9_6mbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:flag-stroke-16" {...props}></Icon>
