<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/g/gwp2jwycy.css';
import '../../css/p/pas470bde.css';
import '../../css/d/dt-wanbxy.css';
import '../../css/a/ay-mwcklb.css';
import '../../css/o/o_ea411kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="gwp2jwycy"/><path class="pas470bde"/><path class="dt-wanbxy"/><path class="ay-mwcklb"/><path class="o_ea411kg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:connection-box" {...props}></Icon>
