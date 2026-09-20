<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/u/u4l0vjnhk.css';
import '../../css/u/ujkx2actq.css';
import '../../css/g/gcoa79bur.css';
import '../../css/j/jp0ue7rnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><circle class="u4l0vjnhk"/><circle class="ujkx2actq"/><path class="gcoa79bur"/><path class="jp0ue7rnb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:face-neutral" {...props}></Icon>
