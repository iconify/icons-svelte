<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gw1pqjbou.css';
import '../../css/c/c24i1_r7s.css';
import '../../css/q/q2lpa00qg.css';
import '../../css/n/nfb842b_s.css';
import '../../css/k/kspoj7vnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="gw1pqjbou"/><path class="c24i1_r7s"/><path class="q2lpa00qg"/><path class="nfb842b_s"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:angle-down-circle" {...props}></Icon>
