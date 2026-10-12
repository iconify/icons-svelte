<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nwg9p5dzv.css';
import '../../css/v/vhrm6lbpx.css';
import '../../css/f/fvw1smy5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nwg9p5dzv"/><path class="vhrm6lbpx"/><path class="fvw1smy5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:dices-duotone" {...props}></Icon>
