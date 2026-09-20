<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohrnlbcwc.css';
import '../../css/z/zxdaapb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ohrnlbcwc"/><path class="zxdaapb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:crosshairs-16" {...props}></Icon>
