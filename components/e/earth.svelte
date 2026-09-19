<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/g/geju8gabu.css';
import '../../css/c/ccdrcabtz.css';
import '../../css/d/dgbqpihnp.css';
import '../../css/r/raqta9bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path clip-rule="evenodd" class="geju8gabu"/><path class="ccdrcabtz"/><path clip-rule="evenodd" class="dgbqpihnp"/><path class="raqta9bwc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:earth" {...props}></Icon>
