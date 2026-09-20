<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijp_u1bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijp_u1bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:hexagon" {...props}></Icon>
