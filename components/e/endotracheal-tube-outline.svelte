<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wy1qmwb1c.css';
import '../../css/p/pfww3mgru.css';
import '../../css/d/d9kll0v9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="wy1qmwb1c"/><path clip-rule="evenodd" class="pfww3mgru"/><path class="d9kll0v9v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:endotracheal-tube-outline" {...props}></Icon>
