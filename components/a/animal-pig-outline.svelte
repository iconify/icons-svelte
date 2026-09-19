<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fqgjk-b4m.css';
import '../../css/o/oh3h2lnrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="fqgjk-b4m"/><path clip-rule="evenodd" class="oh3h2lnrv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:animal-pig-outline" {...props}></Icon>
