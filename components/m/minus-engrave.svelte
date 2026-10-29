<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lvmi_5btw.css';
import '../../css/s/svuiypvdj.css';
import '../../css/z/z8g2jgblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lvmi_5btw"/><path class="svuiypvdj wm-shadow"/><path class="z8g2jgblp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:minus-engrave" {...props}></Icon>
