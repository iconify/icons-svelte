<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w29pu9vcg.css';
import '../../css/x/xw0-qqx6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="w29pu9vcg"/><path clip-rule="evenodd" class="xw0-qqx6q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:contraceptive-voucher" {...props}></Icon>
