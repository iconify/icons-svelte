<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/yawb1gbpi.css';
import '../../css/p/psnkz2bcb.css';
import '../../css/c/cqb1wcccy.css';
import '../../css/q/qr4ochb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wm-k yawb1gbpi"/><path class="psnkz2bcb wm-k"/><circle class="cqb1wcccy wm-a"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:camera-off-duo" {...props}></Icon>
