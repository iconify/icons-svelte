<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cna9ecbpk.css';
import '../../css/z/zinrowbcn.css';
import '../../css/y/y5hl0bc-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cna9ecbpk"/><path clip-rule="evenodd" class="zinrowbcn"/><path class="y5hl0bc-e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-ab-p-24px" {...props}></Icon>
