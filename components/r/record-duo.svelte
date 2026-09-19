<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lafhkbbho.css';
import '../../css/o/orpw_qu3f.css';
import '../../css/w/w4vxnac6h.css';
import '../../css/w/wk9-pwuua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lafhkbbho"/><path class="orpw_qu3f"/><path class="w4vxnac6h"/><path class="wk9-pwuua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:record-duo" {...props}></Icon>
