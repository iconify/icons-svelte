<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rdao9ob4q.css';
import '../../css/j/jnx_yfj0m.css';
import '../../css/i/idyq5q_2w.css';
import '../../css/l/l5d48xbhd.css';
import '../../css/k/kt3-oo4th.css';
import '../../css/n/nkwfcsn2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="rdao9ob4q"/><path class="jnx_yfj0m"/><path class="idyq5q_2w"/><path class="l5d48xbhd"/><path class="kt3-oo4th"/><path class="nkwfcsn2t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:gmr" {...props}></Icon>
