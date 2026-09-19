<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyprt8xil.css';
import '../../css/c/czi-3ob_q.css';
import '../../css/u/u_tnrpbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="jyprt8xil"/><path class="czi-3ob_q"/><path class="u_tnrpbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-reddit" {...props}></Icon>
