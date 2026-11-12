<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqmp0xvom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uqmp0xvom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mediamtx-light" {...props}></Icon>
