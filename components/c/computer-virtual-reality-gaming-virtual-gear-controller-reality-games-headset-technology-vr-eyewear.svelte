<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmxhs-b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="nmxhs-b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-virtual-reality-gaming-virtual-gear-controller-reality-games-headset-technology-vr-eyewear" {...props}></Icon>
