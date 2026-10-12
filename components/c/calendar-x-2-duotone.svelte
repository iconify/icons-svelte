<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qy4g72xnx.css';
import '../../css/p/p3poopb-f.css';
import '../../css/h/hxngk6b1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qy4g72xnx"/><path class="p3poopb-f"/><path class="hxngk6b1m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-x-2-duotone" {...props}></Icon>
