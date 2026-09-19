<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jullk8bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jullk8bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:microchip" {...props}></Icon>
