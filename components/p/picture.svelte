<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsw5so5pt.css';
import '../../css/t/tm3avkrlq.css';
import '../../css/g/g5s0ynieo.css';
import '../../css/k/ks7wf3l0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tsw5so5pt"/><circle class="tm3avkrlq"/><path class="g5s0ynieo"/><path class="ks7wf3l0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:picture" {...props}></Icon>
