<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/a/ayrv02bwd.css';
import '../../css/a/axt9ohbyr.css';
import '../../css/c/cly7zkdlc.css';
import '../../css/n/ncvieabhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="ayrv02bwd"/><circle class="axt9ohbyr"/><path class="cly7zkdlc"/><path class="ncvieabhv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:cart-outline" {...props}></Icon>
