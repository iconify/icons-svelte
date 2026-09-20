<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc67x7txf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc67x7txf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gas-station-off-outline" {...props}></Icon>
