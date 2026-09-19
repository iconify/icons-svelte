<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc6t_n4ay.css';
import '../../css/c/cqrap-bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc6t_n4ay"/><path class="cqrap-bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-doughnut-chart" {...props}></Icon>
