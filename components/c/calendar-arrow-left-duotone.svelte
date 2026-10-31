<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rminvdhlv.css';
import '../../css/p/p3poopb-f.css';
import '../../css/l/l7rc3p0id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rminvdhlv"/><path class="p3poopb-f"/><path class="l7rc3p0id"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-arrow-left-duotone" {...props}></Icon>
