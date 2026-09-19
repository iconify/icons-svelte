<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/c/cd0y8fbhg.css';
import '../../css/x/x5dbkkbej.css';
import '../../css/f/fee440due.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="cd0y8fbhg"/><circle class="x5dbkkbej"/><circle class="fee440due"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:list-fail" {...props}></Icon>
