<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsm942blq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsm942blq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:details" {...props}></Icon>
