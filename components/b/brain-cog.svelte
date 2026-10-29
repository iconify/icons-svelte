<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lvwj8zv0y.css';
import '../../css/d/d-c_quigx.css';
import '../../css/e/ekmlpmtjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lvwj8zv0y"/><path class="d-c_quigx wm-a"/><path class="ekmlpmtjg wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:brain-cog" {...props}></Icon>
