<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kdtcnac0c.css';
import '../../css/e/eh6lx4har.css';
import '../../css/d/dwevdfbxv.css';
import '../../css/o/ox3_uabnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="kdtcnac0c"/><path clip-rule="evenodd" class="eh6lx4har"/><path class="dwevdfbxv"/><path clip-rule="evenodd" class="ox3_uabnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:flip-1-outline" {...props}></Icon>
