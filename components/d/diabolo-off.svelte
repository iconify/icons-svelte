<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/netsmeake.css';
import '../../css/u/u-k87dwdf.css';
import '../../css/x/xyixtmbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="netsmeake"/><path class="u-k87dwdf"/><path class="xyixtmbhb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:diabolo-off" {...props}></Icon>
