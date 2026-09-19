<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hm448n5sq.css';
import '../../css/y/y_eqqfhlq.css';
import '../../css/k/k7-jbed1z.css';
import '../../css/q/qe6nwyqjs.css';
import '../../css/e/evgrznjfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><rect class="hm448n5sq"/><path class="y_eqqfhlq"/><path clip-rule="evenodd" class="k7-jbed1z"/><path class="qe6nwyqjs"/><path class="evgrznjfa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:printer-print" {...props}></Icon>
