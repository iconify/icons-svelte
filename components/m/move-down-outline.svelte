<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd4mgibiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vd4mgibiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:move-down-outline" {...props}></Icon>
