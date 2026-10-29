<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vgi0-qbpw.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/l/lcou3abui.css';
import '../../css/o/op1x1ovuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vgi0-qbpw"/><path class="qr4ochb5c wm-s"/><path class="lcou3abui"/><path class="op1x1ovuv wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:flag-off-duo" {...props}></Icon>
