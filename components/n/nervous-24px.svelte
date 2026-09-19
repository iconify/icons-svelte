<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l5dsk-k8i.css';
import '../../css/u/u2sn6fb9r.css';
import '../../css/m/m5ap_-bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="l5dsk-k8i"/><path class="u2sn6fb9r"/><path clip-rule="evenodd" class="m5ap_-bph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:nervous-24px" {...props}></Icon>
