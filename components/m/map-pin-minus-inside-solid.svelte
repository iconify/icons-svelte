<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n04d5sb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n04d5sb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:map-pin-minus-inside-solid" {...props}></Icon>
