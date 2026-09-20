<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/o/o30ctab0j.css';
import '../../css/t/th_2fsb0e.css';
import '../../css/d/d-a_qsb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="o30ctab0j"/><path class="th_2fsb0e"/><path class="d-a_qsb5c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:radar-sharp-two-tone" {...props}></Icon>
