<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve_g31b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve_g31b1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hexagon-slice-5" {...props}></Icon>
