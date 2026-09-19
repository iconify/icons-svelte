<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/a/am4lb-bdv.css';
import '../../css/l/ln7fn5cus.css';
import '../../css/s/scyn38bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="am4lb-bdv"/><path class="ln7fn5cus"/><path class="scyn38bvf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:frigate" {...props}></Icon>
