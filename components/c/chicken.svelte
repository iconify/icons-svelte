<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/t/tkm1l-bce.css';
import '../../css/y/youbn_grx.css';
import '../../css/j/j_ff0ybgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="tkm1l-bce"/><path class="youbn_grx"/><path class="j_ff0ybgy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:chicken" {...props}></Icon>
