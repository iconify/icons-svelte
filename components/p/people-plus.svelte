<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mpi1ahbrd.css';
import '../../css/k/kqaa2dvri.css';
import '../../css/w/wv15rjmiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="mpi1ahbrd"/><path clip-rule="evenodd" class="kqaa2dvri"/><path class="wv15rjmiv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:people-plus" {...props}></Icon>
