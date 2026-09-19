<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/h54a1dbvn.css';
import '../../css/k/kf_yp9bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="map-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="h54a1dbvn"/><path class="kf_yp9bvr"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:map-outline" {...props}></Icon>
