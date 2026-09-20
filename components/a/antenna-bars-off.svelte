<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xac6b2u_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xac6b2u_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:antenna-bars-off" {...props}></Icon>
