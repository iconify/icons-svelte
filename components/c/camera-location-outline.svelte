<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erckkwu7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erckkwu7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-location-outline" {...props}></Icon>
