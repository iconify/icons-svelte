<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/q/q0_4c0bwj.css';
import '../../css/x/xx-w1p09b.css';
import '../../css/g/gl91pxq4m.css';
import '../../css/y/yn6dafa7n.css';
import '../../css/s/szrkkkb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="q0_4c0bwj"/><path class="xx-w1p09b"/><path class="gl91pxq4m"/><path class="yn6dafa7n"/><path class="szrkkkb6h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:four-round-point-connection" {...props}></Icon>
