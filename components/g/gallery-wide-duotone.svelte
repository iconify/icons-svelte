<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mmzz96bmf.css';
import '../../css/o/o57sxb6nv.css';
import '../../css/r/r8pl9hbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mmzz96bmf"/><path clip-rule="evenodd" class="o57sxb6nv"/><path class="r8pl9hbsw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gallery-wide-duotone" {...props}></Icon>
