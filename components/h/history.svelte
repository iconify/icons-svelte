<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/t/tu7lv1bwo.css';
import '../../css/l/lwmxsqbjy.css';
import '../../css/h/hygxn_ioi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="tu7lv1bwo"/><path class="lwmxsqbjy"/><path class="hygxn_ioi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:history" {...props}></Icon>
