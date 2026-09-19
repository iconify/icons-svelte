<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/u/uyd20qc5d.css';
import '../../css/x/x6syeybxm.css';
import '../../css/r/r1na0qb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="uyd20qc5d"/><path class="x6syeybxm"/><path class="r1na0qb3v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:health-worker-outline" {...props}></Icon>
