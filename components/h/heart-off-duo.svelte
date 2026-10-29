<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/o44bfh3jr.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/q/qvra2koks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="o44bfh3jr"/><path class="qr4ochb5c wm-s"/><path class="qvra2koks"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heart-off-duo" {...props}></Icon>
