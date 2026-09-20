<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl4nh39pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl4nh39pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:crosshairs-off" {...props}></Icon>
