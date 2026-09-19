<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji7x0bcjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ji7x0bcjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-ppt" {...props}></Icon>
