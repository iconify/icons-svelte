<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a6q71839u.css';
import '../../css/c/c9yhn8fgx.css';
import '../../css/r/ru576oa1k.css';
import '../../css/x/x_u2gpj0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="a6q71839u"/><path class="c9yhn8fgx"/><path clip-rule="evenodd" class="ru576oa1k"/><path class="x_u2gpj0m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-rh-p-outline" {...props}></Icon>
