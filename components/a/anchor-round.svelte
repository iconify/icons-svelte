<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/e/e9bm3i9jh.css';
import '../../css/a/a4ms69b5n.css';
import '../../css/b/bf0_kdbgt.css';
import '../../css/t/trdpk-b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="e9bm3i9jh"/><circle class="a4ms69b5n"/><circle class="bf0_kdbgt"/><circle class="trdpk-b6y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:anchor-round" {...props}></Icon>
