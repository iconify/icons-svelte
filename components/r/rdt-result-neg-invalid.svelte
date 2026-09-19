<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/orag1morv.css';
import '../../css/p/ph3hdab0i.css';
import '../../css/w/wa65fi0wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="orag1morv"/><path clip-rule="evenodd" class="ph3hdab0i"/><path class="wa65fi0wq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:rdt-result-neg-invalid" {...props}></Icon>
