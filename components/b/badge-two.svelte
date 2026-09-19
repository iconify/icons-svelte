<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/w/w7bq11q3s.css';
import '../../css/b/bq_9nmq8p.css';
import '../../css/v/vvnoc_b4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="w7bq11q3s"/><path class="bq_9nmq8p"/><path class="vvnoc_b4o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:badge-two" {...props}></Icon>
