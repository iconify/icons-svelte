<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/n/nqwhu1s7a.css';
import '../../css/o/ox6d5w6du.css';
import '../../css/t/tq2sis96r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="nqwhu1s7a"/><path class="ox6d5w6du"/><path class="tq2sis96r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:local" {...props}></Icon>
