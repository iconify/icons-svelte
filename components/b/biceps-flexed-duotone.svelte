<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mx7m2kb4i.css';
import '../../css/m/mtt6u2npc.css';
import '../../css/v/vt2jqcb8p.css';
import '../../css/b/bvgmm8b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mx7m2kb4i"/><path class="mtt6u2npc"/><path class="vt2jqcb8p"/><path class="bvgmm8b4h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:biceps-flexed-duotone" {...props}></Icon>
