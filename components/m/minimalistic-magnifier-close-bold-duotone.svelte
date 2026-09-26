<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r0xhknb7f.css';
import '../../css/e/e1r0khblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="r0xhknb7f"/><path class="e1r0khblb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifier-close-bold-duotone" {...props}></Icon>
