<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/t/t58456njl.css';
import '../../css/p/ptvu1u_4n.css';
import '../../css/s/ssdl_vbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t58456njl"/><circle class="ptvu1u_4n"/><path class="ssdl_vbpi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:map-pinned" {...props}></Icon>
