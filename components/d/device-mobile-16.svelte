<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox2gpx_xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ox2gpx_xr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:device-mobile-16" {...props}></Icon>
