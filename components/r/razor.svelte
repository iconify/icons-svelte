<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/l/lj8xgwb9t.css';
import '../../css/k/kooq7hlhc.css';
import '../../css/e/e814sabwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><rect class="lj8xgwb9t"/><path class="kooq7hlhc"/><path class="e814sabwa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:razor" {...props}></Icon>
