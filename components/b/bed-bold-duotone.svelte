<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gjg5ynbsr.css';
import '../../css/x/x0mt87bnf.css';
import '../../css/v/va1mprb_y.css';
import '../../css/c/cvam6ekry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gjg5ynbsr"/><path class="x0mt87bnf"/><path class="va1mprb_y"/><path class="cvam6ekry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bed-bold-duotone" {...props}></Icon>
