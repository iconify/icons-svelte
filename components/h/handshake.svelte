<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a39eozb4h.css';
import '../../css/o/oj34xxbcj.css';
import '../../css/k/k5-wqgb-q.css';
import '../../css/d/diyvfeblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="a39eozb4h"/><path class="oj34xxbcj"/><path class="k5-wqgb-q"/><path class="diyvfeblp wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:handshake" {...props}></Icon>
