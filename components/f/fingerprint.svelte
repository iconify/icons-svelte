<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/e/em1eecbma.css';
import '../../css/k/ke0058byd.css';
import '../../css/l/l76rhnbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="em1eecbma"/><path class="ke0058byd"/><path class="l76rhnbaq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:fingerprint" {...props}></Icon>
