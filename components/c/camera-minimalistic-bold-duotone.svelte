<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/erpmo6bnm.css';
import '../../css/x/xvjqgobjy.css';
import '../../css/k/kx3o_bcjy.css';
import '../../css/j/j22c2bb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="erpmo6bnm"/><path clip-rule="evenodd" class="xvjqgobjy"/><path class="kx3o_bcjy"/><path class="j22c2bb7y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:camera-minimalistic-bold-duotone" {...props}></Icon>
