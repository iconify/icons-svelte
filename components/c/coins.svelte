<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/p-nn7p34f.css';
import '../../css/e/eg-dtmkbo.css';
import '../../css/f/fyvi155ol.css';
import '../../css/t/tqnmtibrt.css';
import '../../css/c/cwrfew54d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="p-nn7p34f"/><path class="eg-dtmkbo"/><path class="fyvi155ol"/><path class="tqnmtibrt"/><path class="cwrfew54d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:coins" {...props}></Icon>
