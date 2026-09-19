<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/n/nx5hmg1lc.css';
import '../../css/g/gnr850uhy.css';
import '../../css/h/hl1e5tbjq.css';
import '../../css/a/a-2hqx3ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><rect class="nx5hmg1lc"/><path class="gnr850uhy"/><path clip-rule="evenodd" class="hl1e5tbjq"/><path class="a-2hqx3ud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:calendar-thirty" {...props}></Icon>
