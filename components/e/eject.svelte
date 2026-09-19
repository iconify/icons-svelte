<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw3oggbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":384};
const content = `<path class="iw3oggbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:eject" {...props}></Icon>
