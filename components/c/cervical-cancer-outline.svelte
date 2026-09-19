<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zo8k5kb-x.css';
import '../../css/e/ejrk76bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="zo8k5kb-x"/><path clip-rule="evenodd" class="ejrk76bap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cervical-cancer-outline" {...props}></Icon>
