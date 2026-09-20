<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isc-7v3rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="isc-7v3rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:guidepost" {...props}></Icon>
