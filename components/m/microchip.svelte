<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrvel4b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xrvel4b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:microchip" {...props}></Icon>
