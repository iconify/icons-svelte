<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxa8g1uva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxa8g1uva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-cancelled" {...props}></Icon>
