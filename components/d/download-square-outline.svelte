<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s-mq1skfr.css';
import '../../css/t/t7wl2l2ca.css';
import '../../css/z/zuqh_gv5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s-mq1skfr"/><path class="t7wl2l2ca"/><path clip-rule="evenodd" class="zuqh_gv5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:download-square-outline" {...props}></Icon>
