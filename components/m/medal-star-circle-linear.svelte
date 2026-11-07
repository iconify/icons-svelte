<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xekr-cc0r.css';
import '../../css/l/l_3c_lb_q.css';
import '../../css/q/qxdu-bceo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xekr-cc0r"/><circle class="l_3c_lb_q"/><path class="qxdu-bceo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-star-circle-linear" {...props}></Icon>
