<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cpcm_cbdw.css';
import '../../css/q/qbxn-wb6f.css';
import '../../css/d/d030jw_4r.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cpcm_cbdw"/><path clip-rule="evenodd" class="qbxn-wb6f"/><path clip-rule="evenodd" class="d030jw_4r"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:previous-track-off" {...props}></Icon>
