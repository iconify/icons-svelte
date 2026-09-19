<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bbxdvzjvn.css';
import '../../css/y/ypdia9bkn.css';
import '../../css/m/mxb79nbaf.css';
import '../../css/x/x5ekm4b9c.css';
import '../../css/d/dvl474wgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bbxdvzjvn"/><path clip-rule="evenodd" class="ypdia9bkn"/><path class="mxb79nbaf"/><path class="x5ekm4b9c"/><path class="dvl474wgs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:cloud-up-print" {...props}></Icon>
