<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwtp78bsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwtp78bsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gas-water-boiler" {...props}></Icon>
