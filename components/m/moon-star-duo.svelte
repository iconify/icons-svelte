<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/neorgv4af.css';
import '../../css/p/p36q5om8r.css';
import '../../css/x/x74picb7l.css';
import '../../css/s/sfp-qh-hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="neorgv4af"/><path class="p36q5om8r wm-s"/><path class="wm-s x74picb7l"/><path class="sfp-qh-hh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:moon-star-duo" {...props}></Icon>
