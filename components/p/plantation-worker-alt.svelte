<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/svhmzzwpg.css';
import '../../css/a/az0f5oiia.css';
import '../../css/r/rhiflirgq.css';
import '../../css/l/ljkj8kesp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="svhmzzwpg"/><path clip-rule="evenodd" class="az0f5oiia"/><path class="rhiflirgq"/><path class="ljkj8kesp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:plantation-worker-alt" {...props}></Icon>
