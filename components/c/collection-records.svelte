<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/b/bnodaob4x.css';
import '../../css/w/wmhdlspux.css';
import '../../css/v/vt3dtr0_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="bnodaob4x"/><path class="wmhdlspux"/><path class="vt3dtr0_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:collection-records" {...props}></Icon>
