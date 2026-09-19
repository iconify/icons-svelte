<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xi7esbcle.css';
import '../../css/p/pimqc2bvo.css';
import '../../css/e/ehv-evg_q.css';
import '../../css/o/oqynatbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="xi7esbcle"/><path class="pimqc2bvo"/><circle class="ehv-evg_q"/><circle class="oqynatbcn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:peas" {...props}></Icon>
