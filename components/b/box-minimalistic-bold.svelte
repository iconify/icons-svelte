<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/la--7ib8h.css';
import '../../css/e/e06ot6o4h.css';
import '../../css/k/k85dgg62q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="la--7ib8h"/><path class="e06ot6o4h"/><path class="k85dgg62q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:box-minimalistic-bold" {...props}></Icon>
