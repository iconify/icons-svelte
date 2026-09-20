<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnd1_cdki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnd1_cdki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-charging-wireless-50" {...props}></Icon>
