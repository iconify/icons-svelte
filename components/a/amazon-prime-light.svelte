<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffx3t1d0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ffx3t1d0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-prime-light" {...props}></Icon>
