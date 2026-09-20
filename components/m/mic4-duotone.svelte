<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w_bo51blv.css';
import '../../css/e/ev28lhkcq.css';
import '../../css/v/vxxv0vbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="w_bo51blv"/><path class="ev28lhkcq"/><path clip-rule="evenodd" class="vxxv0vbbn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mic4-duotone" {...props}></Icon>
