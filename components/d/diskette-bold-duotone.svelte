<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/aekvrpe8z.css';
import '../../css/f/fwk_2x_mx.css';
import '../../css/a/aw2dxzblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="aekvrpe8z"/><path class="fwk_2x_mx"/><path class="aw2dxzblq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:diskette-bold-duotone" {...props}></Icon>
