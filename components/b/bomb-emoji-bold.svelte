<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rn08x5brb.css';
import '../../css/p/pk2i_1x1h.css';
import '../../css/n/ngo4x72kh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rn08x5brb"/><path clip-rule="evenodd" class="pk2i_1x1h"/><path class="ngo4x72kh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bomb-emoji-bold" {...props}></Icon>
