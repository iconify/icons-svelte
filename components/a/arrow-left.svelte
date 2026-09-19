<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur7gzpbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ur7gzpbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:arrow-left" {...props}></Icon>
