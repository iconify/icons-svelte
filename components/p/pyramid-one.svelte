<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/u/uj507xj1f.css';
import '../../css/l/lhllv9bxt.css';
import '../../css/d/dgn0rl2ke.css';
import '../../css/r/rdjwzdbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="uj507xj1f"/><path class="lhllv9bxt"/><path class="dgn0rl2ke"/><path class="rdjwzdbya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:pyramid-one" {...props}></Icon>
