<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gf_l4bcfr.css';
import '../../css/g/gap_aabgc.css';
import '../../css/z/z656bjbcd.css';
import '../../css/w/w-4_xvbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gf_l4bcfr"/><path clip-rule="evenodd" class="gap_aabgc"/><path class="z656bjbcd"/><path clip-rule="evenodd" class="w-4_xvbmg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:money-bills" {...props}></Icon>
