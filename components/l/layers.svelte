<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/ly52aibmo.css';
import '../../css/x/xrxaul_zl.css';
import '../../css/d/dv0ekmbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ly52aibmo"/><path class="xrxaul_zl"/><path class="dv0ekmbgh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:layers" {...props}></Icon>
