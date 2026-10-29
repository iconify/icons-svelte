<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y_418pbnl.css';
import '../../css/n/nu0etmf-v.css';
import '../../css/d/d1414zbwi.css';
import '../../css/b/b-jt0k5cr.css';
import '../../css/u/ui32hib9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k y_418pbnl"/><path class="nu0etmf-v wm-a"/><path class="d1414zbwi wm-shadow"/><path class="b-jt0k5cr wm-k"/><path class="ui32hib9b wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:crown-engrave" {...props}></Icon>
