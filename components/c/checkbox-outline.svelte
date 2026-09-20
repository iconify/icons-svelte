<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rboetifwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rboetifwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:checkbox-outline" {...props}></Icon>
