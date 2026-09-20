<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yncbdi2uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yncbdi2uy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:patio-heater" {...props}></Icon>
