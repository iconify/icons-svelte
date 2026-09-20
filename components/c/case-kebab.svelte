<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/x/xnajft-bs.css';
import '../../css/p/p1u_g2bvy.css';
import '../../css/p/pxaww4b9h.css';
import '../../css/w/w6_bkqfhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="xnajft-bs"/><path class="p1u_g2bvy"/><circle class="pxaww4b9h"/><path class="w6_bkqfhr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:case-kebab" {...props}></Icon>
