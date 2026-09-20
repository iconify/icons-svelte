<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/px8vwib8v.css';
import '../../css/o/olk-hrbfo.css';
import '../../css/g/g36f5_bfg.css';
import '../../css/u/u3-9r76_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="px8vwib8v"/><path class="olk-hrbfo"/><path class="g36f5_bfg"/><path class="u3-9r76_e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dialog-outline" {...props}></Icon>
