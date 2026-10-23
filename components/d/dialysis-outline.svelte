<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dt7t81_nm.css';
import '../../css/f/fvr250bdj.css';
import '../../css/v/vwy8x5bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="dt7t81_nm"/><path clip-rule="evenodd" class="fvr250bdj"/><path clip-rule="evenodd" class="vwy8x5bnj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:dialysis-outline" {...props}></Icon>
