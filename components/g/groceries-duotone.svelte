<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/simuctb5x.css';
import '../../css/u/uklx4ab3h.css';
import '../../css/n/n171dubne.css';
import '../../css/q/q_hxl1s-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="simuctb5x"/><path class="uklx4ab3h"/><path class="n171dubne"/><path class="q_hxl1s-e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:groceries-duotone" {...props}></Icon>
