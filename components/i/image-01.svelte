<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/e2i1rhbxz.css';
import '../../css/j/jvtjbnueh.css';
import '../../css/u/ufhz_q2qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="e2i1rhbxz"/><path class="jvtjbnueh"/><path class="ufhz_q2qg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:image-01" {...props}></Icon>
