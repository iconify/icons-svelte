<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gngkh0_1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gngkh0_1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:electrical-circuit-and-bolt" {...props}></Icon>
