<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/svbii8bvw.css';
import '../../css/t/tsi2e0_6j.css';
import '../../css/l/lhyyi3z4l.css';
import '../../css/s/s-htz7_sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="svbii8bvw"/><path class="tsi2e0_6j"/><path class="lhyyi3z4l"/><path class="s-htz7_sn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:object-ungroup" {...props}></Icon>
