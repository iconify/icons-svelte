<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k83ygvv2n.css';
import '../../css/s/smchphbbk.css';
import '../../css/l/lh26qe_gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k83ygvv2n"/><path clip-rule="evenodd" class="smchphbbk"/><path clip-rule="evenodd" class="lh26qe_gi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:mobile-outline-24px" {...props}></Icon>
