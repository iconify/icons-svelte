<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfjju0lxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfjju0lxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-saloon" {...props}></Icon>
