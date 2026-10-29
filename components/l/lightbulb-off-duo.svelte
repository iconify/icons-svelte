<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rzdywtb4l.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/e/e7nou4btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="rzdywtb4l"/><path class="qr4ochb5c wm-s"/><path class="e7nou4btv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lightbulb-off-duo" {...props}></Icon>
