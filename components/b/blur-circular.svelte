<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snst5v0nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="snst5v0nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:blur-circular" {...props}></Icon>
