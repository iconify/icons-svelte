<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zdumi8bzq.css';
import '../../css/b/b67rbwqyq.css';
import '../../css/z/z456bob9a.css';
import '../../css/q/q7hgb9n8f.css';
import '../../css/t/ts7s1o_is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="zdumi8bzq"/><path clip-rule="evenodd" class="b67rbwqyq"/><path class="z456bob9a"/><path clip-rule="evenodd" class="q7hgb9n8f"/><path clip-rule="evenodd" class="ts7s1o_is"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:egg-cell-outline" {...props}></Icon>
