<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/gv7w71ggr.css';
import '../../css/g/g5291rc1t.css';
import '../../css/i/i-0pe7g4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="gv7w71ggr wm-k"/><path class="g5291rc1t wm-a"/><path class="i-0pe7g4j wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:battery-charging-gloss" {...props}></Icon>
