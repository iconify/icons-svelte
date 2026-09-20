<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vbp0l5bpj.css';
import '../../css/l/le1o-ibmd.css';
import '../../css/r/rz20dxvoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="vbp0l5bpj"/><path clip-rule="evenodd" class="le1o-ibmd"/><path class="rz20dxvoy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notebook-bookmark-bold" {...props}></Icon>
