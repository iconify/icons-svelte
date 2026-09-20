<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/minr5gc1v.css';
import '../../css/d/d3drq-8cq.css';
import '../../css/v/vr5t-cbds.css';
import '../../css/v/v50u05_ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="minr5gc1v"/><path class="d3drq-8cq"/><path class="vr5t-cbds"/><path class="v50u05_ah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-2x2-close-bold" {...props}></Icon>
