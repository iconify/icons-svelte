<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/ckbwmibsq.css';
import '../../css/c/c6ojcpbik.css';
import '../../css/t/t6t3twame.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ckbwmibsq"/><path class="c6ojcpbik"/><path class="t6t3twame"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:posts-carousel-horizontal-linear" {...props}></Icon>
