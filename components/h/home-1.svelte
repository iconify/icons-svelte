<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz2p7bcuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vz2p7bcuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:home-1" {...props}></Icon>
