<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l_b5ckbap.css';
import '../../css/z/zo6arnkly.css';
import '../../css/e/eo2tmu8cn.css';
import '../../css/f/fr8pgfmxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="l_b5ckbap"/><path clip-rule="evenodd" class="zo6arnkly"/><path class="eo2tmu8cn"/><path class="fr8pgfmxn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:kayak" {...props}></Icon>
