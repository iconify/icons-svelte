<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mzfuw8b7e.css';
import '../../css/p/p_z7rc6xw.css';
import '../../css/p/pmb-dxz1w.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mzfuw8b7e"/><path class="p_z7rc6xw"/><path clip-rule="evenodd" class="pmb-dxz1w"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:paint-pallet-off" {...props}></Icon>
