<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h18guyucc.css';
import '../../css/t/t2eh-yxwi.css';
import '../../css/g/gfgxpybux.css';
import '../../css/h/h-sspho8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="h18guyucc"/><path class="t2eh-yxwi"/><path class="gfgxpybux"/><path class="h-sspho8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:camera-duo" {...props}></Icon>
