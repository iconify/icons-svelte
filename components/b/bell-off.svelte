<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pck1mgbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pck1mgbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bell-off" {...props}></Icon>
