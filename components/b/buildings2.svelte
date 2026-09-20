<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7fmnlb4r.css';
import '../../css/i/ifroi7b3s.css';
import '../../css/l/llfe_abfd.css';
import '../../css/u/utsg_1-6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="ifroi7b3s"/><path class="llfe_abfd"/><path class="utsg_1-6m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:buildings2" {...props}></Icon>
