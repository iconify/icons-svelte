<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tyc3wod7f.css';
import '../../css/b/bn-fczxak.css';
import '../../css/u/uc23p5bxt.css';
import '../../css/l/lwtwrjtki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tyc3wod7f wm-k"/><path class="bn-fczxak wm-a"/><path class="uc23p5bxt wm-k"/><path class="lwtwrjtki wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rainbow-sketch" {...props}></Icon>
