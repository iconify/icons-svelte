<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-d14a6-i.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lbj5iacpc.css';
import '../../css/j/jaqjjdvqb.css';
import '../../css/d/d-l5n7bpd.css';
import '../../css/e/eo_76b8fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-d14a6-i secondary"/><g class="dt0cm9dhy primary"><path class="lbj5iacpc"/><path class="jaqjjdvqb"/><path class="d-l5n7bpd"/><path class="eo_76b8fd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:printer-off-duo" {...props}></Icon>
