<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mxaafzbto.css';
import '../../css/s/s44rk8z4u.css';
import '../../css/e/e8odqpb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mxaafzbto"/><path clip-rule="evenodd" class="s44rk8z4u"/><path class="e8odqpb8b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:i-documents-denied-outline-24px" {...props}></Icon>
