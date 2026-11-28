<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/khi7kz-fr.css';
import '../../css/f/fhijb1c4d.css';
import '../../css/x/xdc556bol.css';
import '../../css/h/hfirngbmd.css';
import '../../css/x/xc1ugqj_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="khi7kz-fr"/><path class="fhijb1c4d"/><path class="xdc556bol"/><path class="hfirngbmd"/><path class="xc1ugqj_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:gate-xor" {...props}></Icon>
