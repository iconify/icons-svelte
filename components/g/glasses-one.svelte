<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/c/crirhg0qe.css';
import '../../css/c/ccom-1_zn.css';
import '../../css/o/ofgf3ebhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="crirhg0qe"/><circle transform="matrix(-1 0 0 1 33.5 24.5)" class="ccom-1_zn"/><path class="ofgf3ebhn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:glasses-one" {...props}></Icon>
