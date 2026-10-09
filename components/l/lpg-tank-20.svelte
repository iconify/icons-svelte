<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7ro5gmkv.css';
import '../../css/k/kbep-sbgp.css';
import '../../css/k/km0u10_mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y7ro5gmkv"/><path class="kbep-sbgp"/><path class="km0u10_mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lpg-tank-20" {...props}></Icon>
