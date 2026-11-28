<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk6i65b_n.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/p2uslcb4q.css';
import '../../css/p/pv5w52brh.css';
import '../../css/y/yz1e5bbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk6i65b_n secondary"/><g class="dt0cm9dhy primary"><path class="p2uslcb4q"/><path class="pv5w52brh"/><path class="yz1e5bbsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:frisbee-duo" {...props}></Icon>
