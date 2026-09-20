<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcyas_bmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcyas_bmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bell-warning" {...props}></Icon>
