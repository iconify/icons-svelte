<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/x/xo2z99k5u.css';
import '../../css/q/qp8wrac1e.css';
import '../../css/o/ofgf3ebhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="xo2z99k5u"/><circle transform="matrix(-1 0 0 1 33.5 24.5)" class="qp8wrac1e"/><path class="ofgf3ebhn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:glasses-one" {...props}></Icon>
