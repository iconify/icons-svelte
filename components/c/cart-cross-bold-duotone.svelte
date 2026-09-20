<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ihi5mdelv.css';
import '../../css/i/iva9usw6m.css';
import '../../css/v/v1mxnhbir.css';
import '../../css/t/t0v0bebny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ihi5mdelv"/><path class="iva9usw6m"/><path class="v1mxnhbir"/><path class="t0v0bebny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-cross-bold-duotone" {...props}></Icon>
