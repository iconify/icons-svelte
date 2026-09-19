<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/w/w0j83f0iw.css';
import '../../css/m/mh46jehah.css';
import '../../css/t/tabomebrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="w0j83f0iw"/><path class="mh46jehah"/><path class="tabomebrq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:file-excel" {...props}></Icon>
