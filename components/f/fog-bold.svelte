<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ucnfbmfrx.css';
import '../../css/k/k5227db7l.css';
import '../../css/j/jwg3u8mon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ucnfbmfrx"/><path class="k5227db7l"/><path class="jwg3u8mon"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:fog-bold" {...props}></Icon>
