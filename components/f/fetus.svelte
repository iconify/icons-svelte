<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oe2s1dbyb.css';
import '../../css/h/hx-__9b7l.css';
import '../../css/m/moq29-b6s.css';
import '../../css/j/jvcxt3txs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="oe2s1dbyb"/><path class="hx-__9b7l"/><path clip-rule="evenodd" class="moq29-b6s"/><path clip-rule="evenodd" class="jvcxt3txs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:fetus" {...props}></Icon>
