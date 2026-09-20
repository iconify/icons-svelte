<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/u/uotk91dww.css';
import '../../css/p/pytfwacmq.css';
import '../../css/t/tzk3rsaex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="n1lsf0bnc"><circle class="uotk91dww"/><circle class="pytfwacmq"/><circle class="tzk3rsaex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:menu-horizontal" {...props}></Icon>
