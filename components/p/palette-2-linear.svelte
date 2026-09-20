<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mz90dcccr.css';
import '../../css/v/va0wxdzar.css';
import '../../css/z/zzoxeseho.css';
import '../../css/f/fwccf37wm.css';
import '../../css/m/makdssbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mz90dcccr"/><circle class="va0wxdzar"/><circle class="zzoxeseho"/><path class="fwccf37wm"/><path class="makdssbcx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:palette-2-linear" {...props}></Icon>
