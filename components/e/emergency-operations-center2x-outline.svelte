<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/znkbcobku.css';
import '../../css/y/y-qjcibit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="znkbcobku"/><path clip-rule="evenodd" class="y-qjcibit"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:emergency-operations-center2x-outline" {...props}></Icon>
