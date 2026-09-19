<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/o/omctlvrzx.css';
import '../../css/v/vs1nct1ln.css';
import '../../css/x/xfbnucutj.css';
import '../../css/k/kmn_ztb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="omctlvrzx"/><path class="vs1nct1ln"/><path class="xfbnucutj"/><path class="kmn_ztb-h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:briefcase" {...props}></Icon>
