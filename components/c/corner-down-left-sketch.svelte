<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/af1frba3j.css';
import '../../css/w/wir0vbbwl.css';
import '../../css/t/tqv20l_mm.css';
import '../../css/f/f72lw2b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="af1frba3j wm-k"/><path class="wir0vbbwl wm-a"/><path class="tqv20l_mm wm-k"/><path class="f72lw2b8q wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:corner-down-left-sketch" {...props}></Icon>
