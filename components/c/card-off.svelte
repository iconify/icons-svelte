<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxc_y7qso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":424};
const content = `<path class="pxc_y7qso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:card-off" {...props}></Icon>
