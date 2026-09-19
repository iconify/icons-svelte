<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i_1x96bbx.css';
import '../../css/h/hvfv66fdp.css';
import '../../css/z/z353grbay.css';
import '../../css/p/pscglsbnn.css';
import '../../css/s/sn_olvw3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="i_1x96bbx"/><rect class="hvfv66fdp"/><rect class="z353grbay"/><rect class="pscglsbnn"/><rect class="sn_olvw3r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:box-layout-4" {...props}></Icon>
