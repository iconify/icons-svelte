<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsvmt9l8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zsvmt9l8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:linecap-square-outline" {...props}></Icon>
