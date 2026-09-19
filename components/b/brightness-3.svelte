<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvd_txbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":280,"height":432};
const content = `<path class="vvd_txbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:brightness-3" {...props}></Icon>
