<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kt_p1jb9m.css';
import '../../css/m/mtly36fij.css';
import '../../css/t/tax-v4byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kt_p1jb9m"/><path class="mtly36fij"/><path class="tax-v4byb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hat-glasses-duotone" {...props}></Icon>
