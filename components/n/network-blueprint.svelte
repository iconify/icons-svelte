<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/n/n3ujxhifz.css';
import '../../css/k/kzvy6zb4p.css';
import '../../css/v/vze4wuf6n.css';
import '../../css/a/a1ax18m6x.css';
import '../../css/t/tzjnnfrgr.css';
import '../../css/l/lc1o9abcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="n3ujxhifz wm-deco"/><path class="kzvy6zb4p wm-deco"/><path class="vze4wuf6n wm-deco"/><path class="a1ax18m6x wm-k"/><path class="tzjnnfrgr wm-a"/><path class="lc1o9abcp wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:network-blueprint" {...props}></Icon>
