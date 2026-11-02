<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlk0x0bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlk0x0bsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-pin-x-inside-fill" {...props}></Icon>
