<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/e/e5ys_6byi.css';
import '../../css/s/s6kk7juwe.css';
import '../../css/s/scyn38bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="e5ys_6byi"/><path class="s6kk7juwe"/><path class="scyn38bvf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:frigate" {...props}></Icon>
