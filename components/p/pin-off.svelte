<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/x97f9bb-q.css';
import '../../css/q/q-qnch_8l.css';
import '../../css/q/qr4ochb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="x97f9bb-q"/><path class="q-qnch_8l wm-a"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pin-off" {...props}></Icon>
