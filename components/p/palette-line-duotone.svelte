<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/idco1xbej.css';
import '../../css/r/rifo2czrt.css';
import '../../css/h/hq7o26lao.css';
import '../../css/m/mlq66nbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="idco1xbej"/><path class="rifo2czrt"/><path class="hq7o26lao"/><path class="mlq66nbgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:palette-line-duotone" {...props}></Icon>
