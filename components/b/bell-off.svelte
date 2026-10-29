<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kjmig_qpk.css';
import '../../css/h/hnamav36t.css';
import '../../css/q/qr4ochb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kjmig_qpk"/><path class="hnamav36t wm-a"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bell-off" {...props}></Icon>
