<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/e/ekm_tyd2k.css';
import '../../css/e/eam0xdz_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ekm_tyd2k"/><path class="eam0xdz_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:octahedron" {...props}></Icon>
