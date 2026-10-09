<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkcxx1bzb.css';
import '../../css/w/wo_d300qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mkcxx1bzb"/><path class="wo_d300qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-warning-20" {...props}></Icon>
