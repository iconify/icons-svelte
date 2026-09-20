<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyoxtgb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyoxtgb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:filter-off-outline" {...props}></Icon>
