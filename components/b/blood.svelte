<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mbsc-1b5r.css';
import '../../css/e/eixrv1bce.css';
import '../../css/o/o3h4-07ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="mbsc-1b5r"/><path class="eixrv1bce"/><path class="o3h4-07ri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:blood" {...props}></Icon>
