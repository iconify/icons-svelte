<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w1w87sbbh.css';
import '../../css/u/u50bmlwji.css';
import '../../css/u/u0z041bxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w1w87sbbh"/><path class="u50bmlwji"/><path class="u0z041bxe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-pin-pen-duotone" {...props}></Icon>
