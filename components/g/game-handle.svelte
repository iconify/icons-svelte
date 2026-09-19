<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/p/pqgcbcbrc.css';
import '../../css/x/x1br9q1lf.css';
import '../../css/b/b9guywupb.css';
import '../../css/o/ohf_mjbft.css';
import '../../css/k/k5a1jgb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="pqgcbcbrc"/><path class="x1br9q1lf"/><path class="b9guywupb"/><path class="ohf_mjbft"/><path class="k5a1jgb-g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:game-handle" {...props}></Icon>
