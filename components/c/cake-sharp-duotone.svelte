<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/h/hz78iv51y.css';
import '../../css/x/x2kte-byy.css';
import '../../css/q/qj43urbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hz78iv51y"/><path class="x2kte-byy"/><path class="qj43urbvu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cake-sharp-duotone" {...props}></Icon>
