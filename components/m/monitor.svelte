<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/t/ttjl0ecfp.css';
import '../../css/v/vce1w3ven.css';
import '../../css/v/vlsgay-ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="ttjl0ecfp"/><path clip-rule="evenodd" class="vce1w3ven"/><path class="vlsgay-ha"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:monitor" {...props}></Icon>
