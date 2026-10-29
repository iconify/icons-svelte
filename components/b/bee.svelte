<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d1xkg3smp.css';
import '../../css/q/qj05ho46r.css';
import '../../css/x/xsnyx0v1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="d1xkg3smp"/><path class="qj05ho46r"/><path class="wm-a xsnyx0v1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bee" {...props}></Icon>
