<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrxl9tfar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrxl9tfar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:car-check" {...props}></Icon>
