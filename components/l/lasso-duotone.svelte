<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yhyxv3b0h.css';
import '../../css/e/eik-sezpc.css';
import '../../css/r/r3rm-cb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yhyxv3b0h"/><path class="eik-sezpc"/><path class="r3rm-cb9f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lasso-duotone" {...props}></Icon>
