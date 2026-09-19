<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pigt72van.css';
import '../../css/l/loci0ub5e.css';
import '../../css/n/n4oalivtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pigt72van"/><path class="loci0ub5e"/><path class="n4oalivtn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-14" {...props}></Icon>
