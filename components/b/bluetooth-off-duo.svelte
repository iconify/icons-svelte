<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fc3kbgmfl.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/a/ahz5bx2fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fc3kbgmfl"/><path class="qr4ochb5c wm-s"/><path class="ahz5bx2fp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bluetooth-off-duo" {...props}></Icon>
