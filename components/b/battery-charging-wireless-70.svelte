<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n666vgbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n666vgbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-charging-wireless-70" {...props}></Icon>
