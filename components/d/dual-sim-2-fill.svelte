<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2d4_eb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2d4_eb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dual-sim-2-fill" {...props}></Icon>
