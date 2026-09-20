<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/q/qvdpjlbmz.css';
import '../../css/y/yv7vu1bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="qvdpjlbmz"/><path class="yv7vu1bvk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:ms-powerpoint-solid" {...props}></Icon>
