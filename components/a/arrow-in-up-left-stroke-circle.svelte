<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns3pdubbz.css';
import '../../css/v/vnep0m7rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ns3pdubbz"/><path class="vnep0m7rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-up-left-stroke-circle" {...props}></Icon>
