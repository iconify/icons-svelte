<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/uw5ylwu1y.css';
import '../../css/z/zk6fj2bpn.css';
import '../../css/p/pltckst1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uw5ylwu1y"/><path class="zk6fj2bpn"/><path class="pltckst1x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:map-pin-star" {...props}></Icon>
