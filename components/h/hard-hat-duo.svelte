<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k75tc6b0u.css';
import '../../css/u/uas-gvbrx.css';
import '../../css/m/mce9chbnc.css';
import '../../css/h/hcaie_vox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="k75tc6b0u"/><path class="uas-gvbrx wm-a"/><path class="mce9chbnc wm-a"/><path class="hcaie_vox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hard-hat-duo" {...props}></Icon>
