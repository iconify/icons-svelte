<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f59prcc4l.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/g/gfjheqbit.css';
import '../../css/w/wsynvg5ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="f59prcc4l"/><path class="qr4ochb5c wm-s"/><path class="gfjheqbit"/><path class="wm-a wsynvg5ce"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:microphone-off-duo" {...props}></Icon>
