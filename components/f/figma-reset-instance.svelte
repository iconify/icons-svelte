<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/x/xi01rxbal.css';
import '../../css/c/ccnbmpbeo.css';
import '../../css/w/wggo06bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="xi01rxbal"/><path class="ccnbmpbeo"/><path class="wggo06bzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:figma-reset-instance" {...props}></Icon>
