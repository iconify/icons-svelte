<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eqydb4bpg.css';
import '../../css/r/rd39nqbvy.css';
import '../../css/o/op837nbch.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="eqydb4bpg"/><path clip-rule="evenodd" class="rd39nqbvy"/><path clip-rule="evenodd" class="op837nbch"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:no-entry-off" {...props}></Icon>
