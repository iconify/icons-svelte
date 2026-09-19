<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/zlv2tpb4e.css';
import '../../css/z/z3h29obsl.css';
import '../../css/m/m-mcntenk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="zlv2tpb4e"/><path class="z3h29obsl"/><path class="m-mcntenk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:arrow-down" {...props}></Icon>
