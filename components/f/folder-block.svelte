<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m0xrrzbhk.css';
import '../../css/p/p-7mrfbjr.css';
import '../../css/q/qs-wobbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="m0xrrzbhk"/><circle class="p-7mrfbjr"/><path class="qs-wobbnb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:folder-block" {...props}></Icon>
