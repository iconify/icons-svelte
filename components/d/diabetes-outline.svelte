<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hvy3labqb.css';
import '../../css/m/mbshinw4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hvy3labqb"/><path class="mbshinw4o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:diabetes-outline" {...props}></Icon>
