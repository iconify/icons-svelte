<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/v/vkrr4mb8s.css';
import '../../css/u/up2i84bwx.css';
import '../../css/q/qbc4_i-8q.css';
import '../../css/g/g2xythr2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="vkrr4mb8s wm-shadow"/><path class="up2i84bwx wm-shadow"/><path class="qbc4_i-8q"/><path class="g2xythr2r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:align-top" {...props}></Icon>
