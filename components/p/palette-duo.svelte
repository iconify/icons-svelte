<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a_3r7i84j.css';
import '../../css/x/xils0pbhd.css';
import '../../css/q/qiuo-kbcb.css';
import '../../css/z/zjapbdb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="a_3r7i84j"/><path class="xils0pbhd"/><path class="qiuo-kbcb"/><path class="zjapbdb7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:palette-duo" {...props}></Icon>
