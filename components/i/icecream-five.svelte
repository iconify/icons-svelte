<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/t/tkw1zoffe.css';
import '../../css/r/rnp50yozo.css';
import '../../css/u/u6d1zuhgm.css';
import '../../css/z/zt8n7mbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="tkw1zoffe"/><path class="rnp50yozo"/><path class="u6d1zuhgm"/><path class="zt8n7mbzz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:icecream-five" {...props}></Icon>
