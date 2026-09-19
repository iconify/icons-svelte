<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thbks7bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="thbks7bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-trending-fill-16" {...props}></Icon>
