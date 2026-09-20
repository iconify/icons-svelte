<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gg2u8wczn.css';
import '../../css/l/lnoo-mkzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gg2u8wczn"/><path clip-rule="evenodd" class="lnoo-mkzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:play-rectangle-expressive" {...props}></Icon>
