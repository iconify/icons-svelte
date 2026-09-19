<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/u/ud1zwkbmp.css';
import '../../css/h/h4md0cc7c.css';
import '../../css/r/rbyeil6uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="ud1zwkbmp"/><path class="h4md0cc7c"/><path class="rbyeil6uw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:nut" {...props}></Icon>
