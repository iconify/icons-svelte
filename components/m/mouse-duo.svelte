<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zb344ebmv.css';
import '../../css/c/cz016_bve.css';
import '../../css/m/mm8lkn_5j.css';
import '../../css/t/tmjo8lbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="zb344ebmv"/><path class="cz016_bve wm-a"/><path class="mm8lkn_5j"/><path class="tmjo8lbfp wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mouse-duo" {...props}></Icon>
