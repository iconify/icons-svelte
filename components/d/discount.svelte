<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/d/dl_ofsy9w.css';
import '../../css/s/sjb29en2p.css';
import '../../css/p/pytt3n7gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="dl_ofsy9w"/><path class="sjb29en2p"/><path class="pytt3n7gc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:discount" {...props}></Icon>
