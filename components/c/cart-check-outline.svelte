<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mafgtablf.css';
import '../../css/q/q-vxnsbbp.css';
import '../../css/k/kw39cfx6s.css';
import '../../css/y/yeb076bmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mafgtablf"/><path clip-rule="evenodd" class="q-vxnsbbp"/><path clip-rule="evenodd" class="kw39cfx6s"/><path clip-rule="evenodd" class="yeb076bmv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-check-outline" {...props}></Icon>
