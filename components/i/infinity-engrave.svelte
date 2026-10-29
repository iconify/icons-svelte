<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jd9mkhbdr.css';
import '../../css/o/omerkobbu.css';
import '../../css/t/tef1dsoih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jd9mkhbdr"/><path class="omerkobbu wm-shadow"/><path class="tef1dsoih"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:infinity-engrave" {...props}></Icon>
