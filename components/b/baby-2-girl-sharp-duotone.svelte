<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/f/fvyxm7bvs.css';
import '../../css/s/sp1mbgw9c.css';
import '../../css/e/e-9alfbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fvyxm7bvs"/><path class="sp1mbgw9c"/><path class="e-9alfbmd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:baby-2-girl-sharp-duotone" {...props}></Icon>
