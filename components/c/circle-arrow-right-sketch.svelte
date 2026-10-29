<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/h7vn52bat.css';
import '../../css/x/x_vesxj5e.css';
import '../../css/j/jva_12v9r.css';
import '../../css/h/hl7p31idu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="h7vn52bat"/><path class="wm-k x_vesxj5e"/><path class="jva_12v9r wm-a"/><path class="hl7p31idu wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-arrow-right-sketch" {...props}></Icon>
