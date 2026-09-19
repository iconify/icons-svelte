<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jzrv52bhz.css';
import '../../css/u/uk2jb6qof.css';
import '../../css/f/fvmubtlcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="jzrv52bhz"/><path clip-rule="evenodd" class="uk2jb6qof"/><path class="fvmubtlcg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:eco-care-outline" {...props}></Icon>
