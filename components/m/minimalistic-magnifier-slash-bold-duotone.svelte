<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r0xhknb7f.css';
import '../../css/c/cjjng6bsx.css';
import '../../css/g/gxfi52bne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><circle class="r0xhknb7f"/><path class="cjjng6bsx"/><path class="gxfi52bne"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifier-slash-bold-duotone" {...props}></Icon>
