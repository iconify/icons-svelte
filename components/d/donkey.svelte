<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chr1acb-v.css';
import '../../css/y/yugwo7b3o.css';
import '../../css/r/r_amhvbap.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/u/ubtitpbsd.css';
import '../../css/p/pod_bnbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="chr1acb-v"/><path class="yugwo7b3o"/><path class="r_amhvbap"/><g class="ij2x_72vy"><path class="ubtitpbsd"/><path class="pod_bnbkb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:donkey" {...props}></Icon>
