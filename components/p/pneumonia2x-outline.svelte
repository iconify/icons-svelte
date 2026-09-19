<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cz9m_1xzq.css';
import '../../css/v/vhcjiqhvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="cz9m_1xzq"/><path clip-rule="evenodd" class="vhcjiqhvb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pneumonia2x-outline" {...props}></Icon>
