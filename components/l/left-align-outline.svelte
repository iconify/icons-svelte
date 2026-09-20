<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfkb83bxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pfkb83bxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:left-align-outline" {...props}></Icon>
