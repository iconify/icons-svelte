<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx-tguzcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx-tguzcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-3d" {...props}></Icon>
