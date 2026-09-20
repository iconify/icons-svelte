<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibs2u_b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibs2u_b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bubble-chart-fill" {...props}></Icon>
