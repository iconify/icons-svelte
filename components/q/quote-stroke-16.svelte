<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6avwpwvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m6avwpwvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:quote-stroke-16" {...props}></Icon>
