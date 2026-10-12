<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nemgs-bvb.css';
import '../../css/z/z3eqn8bxs.css';
import '../../css/p/p3poopb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nemgs-bvb"/><path class="z3eqn8bxs"/><path class="p3poopb-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-arrow-up-duotone" {...props}></Icon>
