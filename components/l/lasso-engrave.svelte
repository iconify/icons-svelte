<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/ptcsdyb2z.css';
import '../../css/m/mtw_nubmh.css';
import '../../css/y/yyja13b7h.css';
import '../../css/k/k56gh1yvu.css';
import '../../css/g/gxjs16b5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ptcsdyb2z wm-k"/><path class="mtw_nubmh wm-a"/><path class="wm-shadow yyja13b7h"/><path class="k56gh1yvu wm-k"/><path class="gxjs16b5s wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lasso-engrave" {...props}></Icon>
