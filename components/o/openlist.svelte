<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhwhbdcmq.css';
import '../../css/x/x_z5bwewf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mhwhbdcmq"/><path class="x_z5bwewf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openlist" {...props}></Icon>
