<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m392x3rmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m392x3rmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-charging-wireless-20" {...props}></Icon>
