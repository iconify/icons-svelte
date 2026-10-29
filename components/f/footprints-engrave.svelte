<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/ban8_0bod.css';
import '../../css/f/fnpjw3bbm.css';
import '../../css/e/elnpcezsu.css';
import '../../css/h/ha-6yibsf.css';
import '../../css/k/k26yyvc5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ban8_0bod wm-k"/><path class="fnpjw3bbm wm-a"/><path class="elnpcezsu wm-shadow"/><path class="ha-6yibsf wm-k"/><path class="k26yyvc5e wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:footprints-engrave" {...props}></Icon>
