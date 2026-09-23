<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/e/em3zn9a_e.css';
import '../../css/v/va9-l_xgz.css';
import '../../css/f/ffc9sli3v.css';
import '../../css/d/ddqtrn1yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="em3zn9a_e"/><path class="va9-l_xgz"/><path class="ffc9sli3v"/><path class="ddqtrn1yy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:lightbulb-sparkles-sharp-duotone" {...props}></Icon>
