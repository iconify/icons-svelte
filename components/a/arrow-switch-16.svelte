<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-1x-c_ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x-1x-c_ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-switch-16" {...props}></Icon>
