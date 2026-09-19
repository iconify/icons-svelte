<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/g/gyuogtbyx.css';
import '../../css/x/xqpxb2bhi.css';
import '../../css/s/sgoo-oy7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="gyuogtbyx"/><circle class="xqpxb2bhi"/><path class="sgoo-oy7b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:open-an-account" {...props}></Icon>
