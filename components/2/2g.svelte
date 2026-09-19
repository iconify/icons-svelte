<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a91pdm37g.css';
import '../../css/c/cd8txwljy.css';
import '../../css/k/klacz1bra.css';
import '../../css/h/h2zgbmbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="a91pdm37g"/><path clip-rule="evenodd" class="cd8txwljy"/><path class="klacz1bra"/><path class="h2zgbmbcp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:2g" {...props}></Icon>
