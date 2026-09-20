<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/k/kuqma2mpi.css';
import '../../css/w/w4k9xcc_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="kuqma2mpi"/><path class="w4k9xcc_d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:cloud-download" {...props}></Icon>
