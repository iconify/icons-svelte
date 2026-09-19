<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/g/ghfgsj2ga.css';
import '../../css/k/k16gn-bll.css';
import '../../css/l/llr_2sbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="ghfgsj2ga"/><path class="k16gn-bll"/><path class="llr_2sbko"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:parking" {...props}></Icon>
