<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qpnl_kb9p.css';
import '../../css/h/hwywffbxj.css';
import '../../css/o/op-uyebei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="qpnl_kb9p"/><path clip-rule="evenodd" class="hwywffbxj"/><path class="op-uyebei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:camera-add-bold-duotone" {...props}></Icon>
