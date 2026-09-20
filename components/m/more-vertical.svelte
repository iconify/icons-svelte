<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wmzeeu32g.css';
import '../../css/p/peiq2hfxm.css';
import '../../css/d/dk6s0gbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle transform="rotate(-90 12 18)" class="wmzeeu32g"/><circle transform="rotate(-90 12 12)" class="peiq2hfxm"/><circle transform="rotate(-90 12 6)" class="dk6s0gbmm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:more-vertical" {...props}></Icon>
