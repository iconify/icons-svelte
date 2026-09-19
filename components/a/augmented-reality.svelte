<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/h/h_cgl-bdl.css';
import '../../css/d/d-5qcb7mz.css';
import '../../css/w/w4xii1z6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="h_cgl-bdl"/><path class="d-5qcb7mz"/><path class="w4xii1z6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:augmented-reality" {...props}></Icon>
