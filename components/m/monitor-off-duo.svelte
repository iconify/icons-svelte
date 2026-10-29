<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/ir-rmujqd.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/g/g3cuk7bic.css';
import '../../css/v/vxuqhab0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ir-rmujqd"/><path class="qr4ochb5c wm-s"/><path class="g3cuk7bic"/><path class="vxuqhab0r wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:monitor-off-duo" {...props}></Icon>
