<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pq-mt92dg.css';
import '../../css/b/b13w1nhed.css';
import '../../css/x/x0x96ubmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pq-mt92dg"/><path class="b13w1nhed"/><path class="x0x96ubmz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layout-panel-left-duotone" {...props}></Icon>
