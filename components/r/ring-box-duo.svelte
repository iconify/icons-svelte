<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/s5k88bbyd.css';
import '../../css/o/ox2v0n22b.css';
import '../../css/b/bxp-4qb3o.css';
import '../../css/e/eycan2bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="s5k88bbyd"/><path class="ox2v0n22b wm-s"/><path class="bxp-4qb3o"/><path class="eycan2bvo wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ring-box-duo" {...props}></Icon>
