<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhghu-bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mhghu-bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lidarr-dark" {...props}></Icon>
