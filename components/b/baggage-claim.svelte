<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/z/zg1it3j5p.css';
import '../../css/g/g1fnoac-l.css';
import '../../css/d/d0qq7oxcw.css';
import '../../css/n/nv3r1zbmr.css';
import '../../css/k/k7ycrutox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zg1it3j5p"/><path class="g1fnoac-l"/><rect class="d0qq7oxcw"/><circle class="nv3r1zbmr"/><circle class="k7ycrutox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:baggage-claim" {...props}></Icon>
