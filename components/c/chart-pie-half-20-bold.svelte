<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k849iebqp.css';
import '../../css/c/cham1t_la.css';
import '../../css/e/ey5fq-bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k849iebqp"/><path class="cham1t_la"/><path class="ey5fq-bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-pie-half-20-bold" {...props}></Icon>
