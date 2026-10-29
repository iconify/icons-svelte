<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fuy23-brh.css';
import '../../css/i/irtzjc7wf.css';
import '../../css/v/vbtrpvbhv.css';
import '../../css/u/ukna4qm-o.css';
import '../../css/j/jzul1pbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fuy23-brh wm-k"/><path class="irtzjc7wf wm-a"/><path class="vbtrpvbhv wm-shadow"/><path class="ukna4qm-o wm-k"/><path class="jzul1pbjt wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cactus-engrave" {...props}></Icon>
