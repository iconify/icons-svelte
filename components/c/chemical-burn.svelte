<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d0nqyubyr.css';
import '../../css/e/e06raxbxf.css';
import '../../css/j/jcn5sbflp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="d0nqyubyr"/><path clip-rule="evenodd" class="e06raxbxf"/><path class="jcn5sbflp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chemical-burn" {...props}></Icon>
