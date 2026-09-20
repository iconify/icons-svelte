<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqgpj95pj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqgpj95pj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:high-occupancy-vehicle-lane-outline" {...props}></Icon>
