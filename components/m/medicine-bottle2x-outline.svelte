<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lt1f3wyyx.css';
import '../../css/i/ilh-kebmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="lt1f3wyyx"/><path clip-rule="evenodd" class="ilh-kebmx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:medicine-bottle2x-outline" {...props}></Icon>
