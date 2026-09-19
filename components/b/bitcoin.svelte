<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mvekuabrc.css';
import '../../css/r/rc7piybql.css';
import '../../css/v/vsbbm2bdu.css';
import '../../css/b/bqfct8bxm.css';
import '../../css/x/xsd125mfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><circle class="mvekuabrc"/><path class="rc7piybql"/><path class="vsbbm2bdu"/><path class="bqfct8bxm"/><path class="xsd125mfh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:bitcoin" {...props}></Icon>
