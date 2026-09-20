<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvbcs1z_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rvbcs1z_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:chevron-right" {...props}></Icon>
