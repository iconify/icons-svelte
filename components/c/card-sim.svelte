<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/rdmvcdwyq.css';
import '../../css/j/j1e9bv-lb.css';
import '../../css/d/d7p62aceu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rdmvcdwyq"/><rect class="j1e9bv-lb"/><path class="d7p62aceu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:card-sim" {...props}></Icon>
