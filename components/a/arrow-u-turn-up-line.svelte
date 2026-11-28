<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qekp_tbjc.css';
import '../../css/h/h2f_239py.css';
import '../../css/k/kds_0_e_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="qekp_tbjc"/><path class="h2f_239py"/><path class="kds_0_e_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-u-turn-up-line" {...props}></Icon>
