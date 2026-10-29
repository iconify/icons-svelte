<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pjyv6h2rt.css';
import '../../css/n/n95lt7x7t.css';
import '../../css/r/r1rrqobgd.css';
import '../../css/m/mi_9ztbfv.css';
import '../../css/z/zoq86zjqi.css';
import '../../css/v/vz-n80b1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pjyv6h2rt"/><path class="n95lt7x7t wm-a"/><path class="r1rrqobgd wm-s"/><path class="mi_9ztbfv wm-k"/><path class="wm-a zoq86zjqi"/><path class="vz-n80b1y wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heart-gift-sketch" {...props}></Icon>
