<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/ot56pi4cg.css';
import '../../css/y/ydz_1jyli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ot56pi4cg"/><path clip-rule="evenodd" class="ydz_1jyli"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:oesophagus-cancer" {...props}></Icon>
