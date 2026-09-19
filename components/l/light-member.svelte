<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/b/bufrfgx_w.css';
import '../../css/v/vk38bysgy.css';
import '../../css/h/h1nxzy2nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="bufrfgx_w"/><path class="vk38bysgy"/><path class="h1nxzy2nz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:light-member" {...props}></Icon>
