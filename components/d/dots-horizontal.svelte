<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rwdyu4blt.css';
import '../../css/s/skr69mb3d.css';
import '../../css/t/t-n--fb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><rect class="rwdyu4blt"/><rect class="skr69mb3d"/><rect class="t-n--fb8n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:dots-horizontal" {...props}></Icon>
