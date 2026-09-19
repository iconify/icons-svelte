<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/myj_5-bhn.css';
import '../../css/f/fmveuubpm.css';
import '../../css/c/c6oktlogx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="myj_5-bhn"/><path clip-rule="evenodd" class="fmveuubpm"/><path class="c6oktlogx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:monitor-off" {...props}></Icon>
