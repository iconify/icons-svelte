<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/boxufibmx.css';
import '../../css/o/o1_eg2b-k.css';
import '../../css/q/qaiwobb2g.css';
import '../../css/d/dxplmnb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="boxufibmx"/><path class="o1_eg2b-k"/><path class="qaiwobb2g"/><path class="dxplmnb3y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:document-2-line-duotone" {...props}></Icon>
