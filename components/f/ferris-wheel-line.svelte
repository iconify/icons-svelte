<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvg9x3bmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvg9x3bmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ferris-wheel-line" {...props}></Icon>
