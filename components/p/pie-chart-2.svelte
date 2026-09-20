<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0n9dqb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0n9dqb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pie-chart-2" {...props}></Icon>
