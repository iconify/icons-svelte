<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-4ez0gln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j-4ez0gln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:path-outline" {...props}></Icon>
