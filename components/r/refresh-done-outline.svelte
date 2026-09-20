<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv-yu1hyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xv-yu1hyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:refresh-done-outline" {...props}></Icon>
