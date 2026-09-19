<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/d/drjnalbik.css';
import '../../css/g/g98q0dbmh.css';
import '../../css/j/jqjx1ob6l.css';
import '../../css/d/ddi291rxc.css';
import '../../css/x/xwg81gcfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="drjnalbik"/><path class="g98q0dbmh"/><path class="jqjx1ob6l"/><path class="ddi291rxc"/><path class="xwg81gcfv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:document-folder" {...props}></Icon>
