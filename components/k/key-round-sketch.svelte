<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/okusuaboz.css';
import '../../css/m/msynidc3r.css';
import '../../css/l/lzsxj9r9o.css';
import '../../css/r/r7k_16bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="okusuaboz"/><path class="msynidc3r wm-k"/><path class="lzsxj9r9o wm-k"/><path class="r7k_16bhv wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:key-round-sketch" {...props}></Icon>
