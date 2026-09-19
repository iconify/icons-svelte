<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/au-phnwrn.css';
import '../../css/v/v2o4ilcrp.css';
import '../../css/a/aqpsapbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="au-phnwrn"/><path class="v2o4ilcrp"/><path clip-rule="evenodd" class="aqpsapbet"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-pressure" {...props}></Icon>
