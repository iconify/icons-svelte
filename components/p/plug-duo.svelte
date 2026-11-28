<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kag-7rzzi.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rr5eggbpd.css';
import '../../css/i/istu5egkh.css';
import '../../css/x/xcpnxtbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kag-7rzzi secondary"/><g class="dt0cm9dhy primary"><path class="rr5eggbpd"/><path class="istu5egkh"/><path class="xcpnxtbeg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:plug-duo" {...props}></Icon>
