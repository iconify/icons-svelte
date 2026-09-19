<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b2_koxsvx.css';
import '../../css/q/qhc1lsu-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b2_koxsvx"/><path clip-rule="evenodd" class="qhc1lsu-v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cpu-chip-solid" {...props}></Icon>
