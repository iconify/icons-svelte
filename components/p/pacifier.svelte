<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/mlpd71upt.css';
import '../../css/u/uc-l12bvo.css';
import '../../css/s/s-eh6tbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="mlpd71upt"/><path class="uc-l12bvo"/><path class="s-eh6tbeb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:pacifier" {...props}></Icon>
