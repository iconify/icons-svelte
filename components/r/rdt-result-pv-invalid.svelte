<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/ncq4rhxwl.css';
import '../../css/i/ihl9zebzu.css';
import '../../css/f/fg8vwubln.css';
import '../../css/u/undon46og.css';
import '../../css/c/c590xtbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ncq4rhxwl"/><path class="ihl9zebzu"/><path clip-rule="evenodd" class="fg8vwubln"/><path class="undon46og"/><path clip-rule="evenodd" class="c590xtbuw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:rdt-result-pv-invalid" {...props}></Icon>
