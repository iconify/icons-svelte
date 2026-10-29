<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/ue5yfeb0t.css';
import '../../css/q/qda327bnf.css';
import '../../css/o/ot7ug_ubs.css';
import '../../css/e/e_jnf7h6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ue5yfeb0t wm-k"/><path class="qda327bnf wm-shadow"/><path class="ot7ug_ubs wm-k"/><path class="e_jnf7h6d wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:croissant-engrave" {...props}></Icon>
