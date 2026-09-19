<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4yz3fbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l4yz3fbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:parachute-box" {...props}></Icon>
