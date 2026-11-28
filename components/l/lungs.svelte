<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d0rfbr16h.css';
import '../../css/u/ub0c85bqe.css';
import '../../css/u/uwdjx6w4x.css';
import '../../css/k/k2eiih0kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="d0rfbr16h"/><path class="ub0c85bqe"/><path class="uwdjx6w4x"/><path class="k2eiih0kx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:lungs" {...props}></Icon>
