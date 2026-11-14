<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/lgvsbdbea.css';
import '../../css/k/k1dc_j0wb.css';
import '../../css/y/yw-1u0bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lgvsbdbea"/><path class="k1dc_j0wb"/><path class="yw-1u0bgb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-brain-04" {...props}></Icon>
