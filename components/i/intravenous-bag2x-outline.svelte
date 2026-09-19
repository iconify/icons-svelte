<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n4p47rbwq.css';
import '../../css/i/iok8bk2rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="n4p47rbwq"/><path clip-rule="evenodd" class="iok8bk2rv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:intravenous-bag2x-outline" {...props}></Icon>
