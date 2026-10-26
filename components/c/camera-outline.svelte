<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h_90zg5-g.css';
import '../../css/r/rnlzwqbim.css';
import '../../css/k/khjwtz1gt.css';
import '../../css/j/jq0l92hsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="h_90zg5-g"/><path clip-rule="evenodd" class="rnlzwqbim"/><path clip-rule="evenodd" class="khjwtz1gt"/><path clip-rule="evenodd" class="jq0l92hsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:camera-outline" {...props}></Icon>
