<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/x/xh09az3_x.css';
import '../../css/m/mhir002ms.css';
import '../../css/n/nrm7n3bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="xh09az3_x"/><path class="mhir002ms"/><circle class="nrm7n3bow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:audio-file" {...props}></Icon>
