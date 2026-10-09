<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz8vwp2ry.css';
import '../../css/y/y854psd3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yz8vwp2ry"/><path class="y854psd3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gear-20-bold" {...props}></Icon>
