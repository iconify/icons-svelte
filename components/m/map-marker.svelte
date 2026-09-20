<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irg2cubto.css';
import '../../css/y/yzp037bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irg2cubto"/><path class="yzp037bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:map-marker" {...props}></Icon>
