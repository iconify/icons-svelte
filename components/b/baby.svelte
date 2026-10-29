<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wc_hv_34n.css';
import '../../css/n/n9-b4x4dp.css';
import '../../css/e/emma5uf1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wc_hv_34n"/><path class="n9-b4x4dp"/><path class="emma5uf1l wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:baby" {...props}></Icon>
