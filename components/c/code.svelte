<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5df2yblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y5df2yblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:code" {...props}></Icon>
