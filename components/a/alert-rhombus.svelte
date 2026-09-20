<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z770qubut.css';
import '../../css/f/fjjtewbdp.css';
import '../../css/h/h5_h89bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z770qubut"/><path class="fjjtewbdp"/><circle transform="matrix(1 0 0 -1 10.75 17.06)" class="h5_h89bsj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:alert-rhombus" {...props}></Icon>
