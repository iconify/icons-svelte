<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/h/hc8pcsbjm.css';
import '../../css/c/cmtd2kblp.css';
import '../../css/k/k9pcsy82o.css';
import '../../css/v/vdtfczwsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="hc8pcsbjm"/><path class="cmtd2kblp"/><path clip-rule="evenodd" class="k9pcsy82o"/><path class="vdtfczwsp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:monitor-camera" {...props}></Icon>
