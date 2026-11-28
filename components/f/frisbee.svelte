<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/p2uslcb4q.css';
import '../../css/p/pv5w52brh.css';
import '../../css/y/yz1e5bbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="p2uslcb4q"/><path class="pv5w52brh"/><path class="yz1e5bbsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:frisbee" {...props}></Icon>
