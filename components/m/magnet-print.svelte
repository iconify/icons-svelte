<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/j/jjk1_ku9t.css';
import '../../css/m/m2ray9b6i.css';
import '../../css/q/qahu-cxms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="jjk1_ku9t"/><path class="m2ray9b6i"/><path class="qahu-cxms"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:magnet-print" {...props}></Icon>
