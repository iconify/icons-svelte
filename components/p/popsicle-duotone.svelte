<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cw3kdccbv.css';
import '../../css/x/x6bs8y2ml.css';
import '../../css/p/pkviv2b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cw3kdccbv"/><path class="x6bs8y2ml"/><path class="pkviv2b2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:popsicle-duotone" {...props}></Icon>
