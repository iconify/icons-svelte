<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ema37gbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ema37gbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hexagon-slice-1" {...props}></Icon>
