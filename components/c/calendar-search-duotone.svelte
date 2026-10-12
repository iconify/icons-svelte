<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lh24j6ihd.css';
import '../../css/p/p3poopb-f.css';
import '../../css/k/kmegsac9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lh24j6ihd"/><path class="p3poopb-f"/><path class="kmegsac9l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-search-duotone" {...props}></Icon>
