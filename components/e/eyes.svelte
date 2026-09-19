<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/b/bssk72b0m.css';
import '../../css/r/r5u72ug_r.css';
import '../../css/o/o1i1dslrl.css';
import '../../css/q/q-37s9qkg.css';
import '../../css/f/fdb0c7n_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="bssk72b0m"/><path class="r5u72ug_r"/><path class="o1i1dslrl"/><path class="q-37s9qkg"/><path class="fdb0c7n_b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:eyes" {...props}></Icon>
