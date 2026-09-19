<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rggfaqb6e.css';
import '../../css/m/mc23xac6v.css';
import '../../css/s/scn74gbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="rggfaqb6e"><path class="mc23xac6v"/><path class="scn74gbpo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:check-correct" {...props}></Icon>
