<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu8xy3b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qu8xy3b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:gauge" {...props}></Icon>
