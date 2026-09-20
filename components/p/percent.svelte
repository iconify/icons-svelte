<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/l/lw1hl556r.css';
import '../../css/k/k0f9fhb0x.css';
import '../../css/y/y1axigmai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="lw1hl556r"/><circle class="k0f9fhb0x"/><circle class="y1axigmai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:percent" {...props}></Icon>
