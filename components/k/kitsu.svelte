<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3fj33wpt.css';
import '../../css/i/ihm7jy0xh.css';
import '../../css/m/mzh_2zvez.css';
import '../../css/q/qbnjm1-8j.css';
import '../../css/k/kpd7u-cql.css';
import '../../css/r/rue2fbori.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d3fj33wpt"/><path class="ihm7jy0xh"/><path class="mzh_2zvez"/><path class="qbnjm1-8j"/><path class="kpd7u-cql"/><path class="rue2fbori"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kitsu" {...props}></Icon>
