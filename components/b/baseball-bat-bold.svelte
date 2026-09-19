<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u9pi01b-p.css';
import '../../css/c/cewtkj5-p.css';
import '../../css/t/tu2vxvb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="u9pi01b-p"/><path class="cewtkj5-p"/><path class="tu2vxvb9y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:baseball-bat-bold" {...props}></Icon>
