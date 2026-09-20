<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rtdqotsqn.css';
import '../../css/s/sryg2hb0f.css';
import '../../css/l/lmj6xn97l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rtdqotsqn"/><path class="sryg2hb0f"/><path clip-rule="evenodd" class="lmj6xn97l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-circle-bold-duotone" {...props}></Icon>
