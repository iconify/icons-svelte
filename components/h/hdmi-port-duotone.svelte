<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l5h6qkb-v.css';
import '../../css/e/ebu5-q53q.css';
import '../../css/a/ai741630p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l5h6qkb-v"/><path class="ebu5-q53q"/><path class="ai741630p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hdmi-port-duotone" {...props}></Icon>
