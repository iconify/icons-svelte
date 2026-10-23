<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jc7j2gb8e.css';
import '../../css/v/vakoxcn_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="jc7j2gb8e"/><path class="vakoxcn_p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:high-temp" {...props}></Icon>
