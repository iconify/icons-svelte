<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd465jbnq.css';
import '../../css/n/nxd-6qb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd465jbnq"/><path class="nxd-6qb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:calendar-minimalistic-bold-duotone" {...props}></Icon>
