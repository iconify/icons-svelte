<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bjlambcfe.css';
import '../../css/e/eik-sezpc.css';
import '../../css/r/r3rm-cb9f.css';
import '../../css/v/vnzjq74em.css';
import '../../css/v/vvl9_5q-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bjlambcfe"/><path class="eik-sezpc"/><path class="r3rm-cb9f"/><path class="vnzjq74em"/><path class="vvl9_5q-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lasso-select-duotone" {...props}></Icon>
