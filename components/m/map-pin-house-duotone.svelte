<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mfvnync4s.css';
import '../../css/z/zxvnpccay.css';
import '../../css/o/oipobtb1t.css';
import '../../css/u/u0z041bxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mfvnync4s"/><path class="zxvnpccay"/><path class="oipobtb1t"/><path class="u0z041bxe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-pin-house-duotone" {...props}></Icon>
