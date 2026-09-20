<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc_irebcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc_irebcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-left-bold-hexagon-outline" {...props}></Icon>
