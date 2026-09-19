<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fv6v78bkd.css';
import '../../css/w/w8_g_240j.css';
import '../../css/g/guod_qb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="fv6v78bkd"/><path class="w8_g_240j"/><path class="guod_qb3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:eject-bold" {...props}></Icon>
