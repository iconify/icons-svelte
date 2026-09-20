<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/x/xruhiv3eq.css';
import '../../css/f/f9d3gkb8a.css';
import '../../css/v/vezdedbox.css';
import '../../css/v/v3ds90c7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xruhiv3eq"/><path class="f9d3gkb8a"/><path class="vezdedbox"/><path class="v3ds90c7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:eye-off-sharp-duotone" {...props}></Icon>
