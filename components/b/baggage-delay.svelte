<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/t/t8lnxgces.css';
import '../../css/n/n6762lb_a.css';
import '../../css/k/kfdh64trl.css';
import '../../css/d/dc83f5wdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="t8lnxgces"/><path class="n6762lb_a"/><path class="kfdh64trl"/><path class="dc83f5wdc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:baggage-delay" {...props}></Icon>
