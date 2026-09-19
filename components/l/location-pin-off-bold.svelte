<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4kr7db0h.css';
import '../../css/o/oc0vi5bvd.css';
import '../../css/n/n09t0lk8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="k4kr7db0h"><path class="oc0vi5bvd"/><path class="n09t0lk8r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:location-pin-off-bold" {...props}></Icon>
