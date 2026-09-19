<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j41nt_b2y.css';
import '../../css/s/saxwgqbsi.css';
import '../../css/x/xtnq2r1jb.css';
import '../../css/k/ki_s5dbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="j41nt_b2y"/><path class="saxwgqbsi"/><path clip-rule="evenodd" class="xtnq2r1jb"/><path class="ki_s5dbae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:close-remind" {...props}></Icon>
