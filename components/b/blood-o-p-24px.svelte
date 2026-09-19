<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eqvg89l9a.css';
import '../../css/e/e-f139s-v.css';
import '../../css/i/ixjaemx-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="eqvg89l9a"/><path class="e-f139s-v"/><path clip-rule="evenodd" class="ixjaemx-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-o-p-24px" {...props}></Icon>
