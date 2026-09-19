<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/le33hqf6m.css';
import '../../css/w/wz94lmb_y.css';
import '../../css/o/o57o9vpnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="le33hqf6m"/><path clip-rule="evenodd" class="wz94lmb_y"/><path class="o57o9vpnw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:edit" {...props}></Icon>
