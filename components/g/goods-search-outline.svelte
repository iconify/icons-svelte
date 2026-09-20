<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5rixzbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j5rixzbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:goods-search-outline" {...props}></Icon>
