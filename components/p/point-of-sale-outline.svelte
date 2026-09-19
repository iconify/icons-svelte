<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/k/k84t0ebpb.css';
import '../../css/p/pj4r5mw8r.css';
import '../../css/h/hnzhq2bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><rect class="k84t0ebpb"/><path class="pj4r5mw8r"/><path class="hnzhq2bzi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:point-of-sale-outline" {...props}></Icon>
